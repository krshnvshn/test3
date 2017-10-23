#include <iostream>
#include <strstream>
using namespace std;
int main()
{
    char w[100];
     printf("Vvedi stroku:"); gets(w);
    istrstream is(w);
    char s[100];
    while(is>>s)
    {
        int L=strlen(s);
        char t=s[1];
        s[1]=s[L-1];
        s[L-1]=t;
        cout<<s<<' ';
    }
             cout<<endl;
    system("pause");
    return 0;
}
