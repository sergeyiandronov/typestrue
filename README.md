```
#include <iostream>
#include <limits>

using namespace std;

int main() {
    cout  << "bool "<< sizeof( bool) << "  ("<< numeric_limits<bool>::min()<<","<<numeric_limits<bool>::max()<<")" << endl;

    cout << "char16_t "<< sizeof( char16_t) << "  ("<< numeric_limits<char16_t>::min()<<","<<numeric_limits<char16_t>::max()<<")"<< endl;
    cout <<"char32_t " << sizeof( char32_t) << "  ("<< numeric_limits<char32_t>::min()<<","<<numeric_limits<char32_t>::max()<<")" << endl;
    cout << "char "<< sizeof( char) << "  ("<< numeric_limits<char16_t>::min()<<","<<numeric_limits<char16_t>::max()<<")" <<endl;
    cout <<"unsigned char " << sizeof( unsigned char)<< "  ("<< (int)numeric_limits<unsigned char>::min()<<","<<(int)numeric_limits<unsigned char>::max()<<")" <<  endl;
    cout <<"signed char " << sizeof( signed char)<< "  ("<< (int)numeric_limits<signed char>::min()<<","<<(int)numeric_limits<signed char>::max()<<")" <<  endl;

    cout <<"wchar_t " << sizeof( wchar_t)<< "  ("<< (int)numeric_limits<wchar_t>::min()<<","<<(int)numeric_limits<wchar_t>::max()<<")" <<  endl;

    cout <<"long long " << sizeof( long long)<< "  ("<< numeric_limits<long long>::min()<<","<<numeric_limits<long long>::max()<<")" <<  endl;
    cout << "long "<< sizeof( long) << "  ("<< numeric_limits<long>::min()<<","<<numeric_limits<long>::max()<<")" <<  endl;
    cout <<"int " << sizeof( int) << "  ("<< numeric_limits<int>::min()<<","<<numeric_limits<int>::max()<<")" << endl;
    cout << "float " << sizeof( float)<< "  ("<< numeric_limits<float>::min()<<","<<numeric_limits<float>::max()<<")" <<  endl;
    cout << " double "<< sizeof( double) << "  ("<< numeric_limits<double>::min()<<","<<numeric_limits<double>::max()<<")" <<  endl;
    cout << "short "<< sizeof( short) << "  ("<< numeric_limits<short>::min()<<","<<numeric_limits<short>::max()<<")" << endl;
    cout << "long double " << sizeof( long double) << "  ("<< numeric_limits<long double>::min()<<","<<numeric_limits<long double>::max()<<")" <<  endl;


    cin.get();
    return 0;
}
```
```
bool 1  (0,1)
char16_t 2  (0,65535)
char32_t 4  (0,4294967295)
char 1  (0,65535)
unsigned char 1  (0,255)
signed char 1  (-128,127)
wchar_t 4  (-2147483648,2147483647)
long long 8  (-9223372036854775808,9223372036854775807)
long 8  (-9223372036854775808,9223372036854775807)
int 4  (-2147483648,2147483647)
float 4  (1.17549e-38,3.40282e+38)
 double 8  (2.22507e-308,1.79769e+308)
short 2  (-32768,32767)
long double 16  (3.3621e-4932,1.18973e+4932)
```
