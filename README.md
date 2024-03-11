#include <iostream>

using namespace std;

int main()
{
   cout << " Nama : Valentino Silalahi " << endl;
   cout << " Nim  : 2310431015 " << endl;
   //Program Menghitung IP

   float fd,kd,bm,pm,kl,ad,ag,bi,ip;
   int sfd,skd,sbm,spm,skl,sad,sag,sbi,ts;

   cout << " Masukkan nilai fisika dasar = "; cin >>fd;
   cout << " Masukkan sks fisika dasar = "; cin >>sfd;

   cout << " Masukkan nilai kimia dasar = "; cin >>kd;
   cout << " Masukkan sks kimia dasar = "; cin >>skd;

   cout << " Masukkan nilai b.ing mat = "; cin >>bm;
   cout << " Masukkan sks b.ing mat = "; cin >>sbm;

   cout << " Masukkan nilai pengmat = "; cin >>pm;
   cout << " Masukkan sks pengmat = "; cin >>spm;

   cout << " Masukkan nilai kalkulus 1 = "; cin >>kl;
   cout << " Masukkan sks kalkulus 1 = "; cin >>skl;

   cout << " Masukkan nilai analisis data = "; cin >>ad;
   cout << " Masukkan sks analisis data = "; cin >>sad;

   cout << " Masukkan nilai agama = "; cin >>ag;
   cout << " Masukkan sks agama = "; cin >>sag;

   cout << " Masukkan nilai b.indonesia = "; cin >>bi;
   cout << " Masukkan sks b.indonesia = "; cin >>sbi;

   ts=sfd+skd+sbm+spm+skl+sad+sag+sbi;

   ip=((fd*sfd)+(kd*skd)+(bm*sbm)+(pm*spm)+(kl*skl)+(ad*sad)+(ag*sag)+(bi*sbi))/ts;

   cout << " total sks semester ini = ";
   cout <<ts<<endl;

   cout << " IP anda pada semester ini = ";
   cout <<ip<<endl;
}
