# fe


#include <conio.h>
#include <iostream.h>

float a[10][10];
int n;
void nhap();
void xuat();
void doicot(int, int);
void truhang(int, int);
float dinhthuc();

void main()
{
	clrscr();
	cout << "Nhap kich thuoc ma tran vuong a: so hang = so cot<10, n=";
	cin >> n;
	cout << "Nhap ma tran a :\n";
	nhap();
	cout << "\nMa tran A :\n";
	xuat();
	cout << "\n\nDinh thuc ma tran A :" << dinhthuc();
}
