# stack01

int main() {
    TwoStack ts(5);   // Create one TwoStack object with size 5
    
    ts.push1(10);
    ts.push2(20);
    ts.push1(30);
    ts.push2(40);

    cout << ts.pop1() << endl;  // Output: 30
    cout << ts.pop2() << endl;  // Output: 40
    
    return 0;
}
g++ twostack.cpp -o twostack
stack s1(2), s2(2);
TwoStack s1(2);
s1.push1(20);
s1.push2(10);
