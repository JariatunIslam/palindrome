# palindrome
#include <iostream>
#include <queue>
#include <stack>
using namespace std;

class Solution {
    //Write your code here
        stack<char> s1;
        queue<char> q1;

        public:
        void pushCharacter(char a){
                s1.push(a);
        }
        void enqueueCharacter(char a){
                q1.push(a);
        }
     char popCharacter(){
            char a;
            a=s1.top();
            s1.pop();
            return a;
        }
        char dequeueCharacter(){
            char a;
            a=q1.front();
            q1.pop();
            return a;


        }
};

int main() {
