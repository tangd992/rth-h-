#include <conio.h>
#include <iostream.h>
#define max 100

void main()
{
	int i, j, n;
	float a[max], tbc, pmax, pmin;
	clrscr();
	cout << "Nhap so phan tu n<" << max << ", n= ";
	cin >> n;
	cout << "Nhap cac phan tu cua mang :\n";
	for (i = 0; i < n; i++)#include <conio.h>
#include <iostream.h>
#define max 100

void main()
{
	int i, j, n;
	float a[max], tbc, pmax, pmin;
	clrscr();
	cout << "Nhap so phan tu n<" << max << ", n= ";
	cin >> n;
	cout << "Nhap cac phan tu cua mang :\n";
	for (i = 0; i < n; i++)
	{
		cout << "A[" << i + 1 << "]=";
		cin >> a[i];
	}

	pmax = pmin = tbc = a[0];
	for (i = 1; i < n; i++)
	{
		tbc += a[i];
		if (pmax < a[i]) pmax = a[i];
		if (pmin > a[i]) pmin = a[i];
	}

	tbc = tbc / n;
	cout << "\nPhan tu max=" << pmax;
	cout << "\nPhan tu min=" << pmin;
	cout << "\nGia tri TBC=" << tbc;
	cout << "\nCac phan tu<TBC:\n";
	for (i = 0; i < n; i++)
		if (a[i] < tbc) cout << a[i] << " ";
	cout << "\nCac phan tu > TBC:\n";
	for (i = 0; i < n; i++)
		if (a[i] > tbc) cout << a[i] << " ";#include <conio.h>
#include <iostream.h>
#define max 100

void main()
{
	int i, j, n;
	float a[max], tbc, pmax, pmin;
	clrscr();
	cout << "Nhap so phan tu n<" << max << ", n= ";
	cin >> n;
	cout << "Nhap cac phan tu cua mang :\n";
	for (i = 0; i < n; i++)
	{
		cout << "A[" << i + 1 << "]=";
		cin >> a[i];
	}

	pmax = pmin = tbc = a[0];
	for (i = 1; i < n; i++)
	{
		tbc += a[i];
		if (pmax < a[i]) pmax = a[i];
		if (pmin > a[i]) pmin = a[i];
	}

	tbc = tbc / n;
	cout << "\nPhan tu max=" << pmax;
	cout << "\nPhan tu min=" << pmin;
	cout << "\nGia tri TBC=" << tbc;
	cout << "\nCac phan tu<TBC:\n";
	for (i = 0; i < n; i++)
		if (a[i] < tbc) cout << a[i] << " ";
	cout << "\nCac phan tu > TBC:\n";
	for (i = 0; i < n; i++)
		if (a[i] > tbc) cout << a[i] << " ";
}
}
	cout << "\nCac phan tu<TBC:\n";
	for (i = 0; i < n; i++)
		if (a[i] < tbc) cout << a[i] << " ";
	cout << "\nCac phan tu > TBC:\n";
	for (i = 0; i < n; i++)
		if (a[i] > tbc) cout << a[i] << " ";
}# rth-h-
