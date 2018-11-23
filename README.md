# Latihan01

" Mengambil Bilangan Terbesar Dari Sejumlah Bilangan "

Deklarasi : 

Integer a,b,c,terbesar; 

Deskripsi : 

          Write(“Masukkan Bilangan Pertama : ”); 

          Read(a); 
          
          Write(“Masukkan Bilangan Kedua : ”); 

          Read(b); 
          
          Write(“Masukkan Bilangan Ketiga : ”); 

          Read(c); 
          
              if (a>b) then 
              
              if (a>c) then write(“Terbesar = ”,a);
              
          else wrie(“Terbesar = ”,c); 
          
          endif else if (b>c) 
          
              then write(“Terbesar = ”,b); 
              
              else write(“Terbesar = ”,c); 
              
              endif 
              
              endif

# Program C++

#include <iostream>

using namespace std;

int main()

{

    int i=0;
    
    int max=0;
    
    int a,x;

    cout << "Masukan jumlah bilangan;";
    
    cin >> a;

    for (i;i<a;i++)  {
    
            cout << "Masukan Bilangan Ke-" << i+1 << ": ";
            
            cin >> x;

            if (x > max)
            
                max= x;
}

    cout << "Bilangan terbesar adalah: " << max << endl;
    
}


# Foto Hasil


# Latihan02

" Mengurutkan Bilangan dari Terkecil sampai Terbesar "

Deklarasi :

Integer a,b,c

Diskripsi :
      
      if (a>b){
      
	    if(b>c)
      
	       cout<< a <<" "<< b <<" "<< c ;
         
	    else{
      
		  if (a<c)
      
			   cout<<a<<" "<<c<<" "<<b;
         
		  else
      
			   cout<<c<<" "<<a<<" "<<b;

	    }
      }
      
      else{
      
	    if (a<c)
  
	       cout<< a <<" "<< b <<" "<< c;
         
	    else{
      
		  if (b>c)
      
		     cout<<b<<" "<<c<<" "<<a;
         
		  else
      
		      cout<<c<<" "<<b<<" "<<a;
      
      endif
      
# Program C++

#include <iostream>
  
using namespace std;

int main()

{
    int a,b,c;
    
    cin>> a >> b >> c;
    
    if (a<b)
    
    {
    
        if (b<c)
        
            cout<<  a << "  " << b << "  " <<c;
            
        else
        
        {
        
            if (a<c)
            
                cout<<  a << "  " << c << "  " <<b;
               
            else
            
                cout << c << "  " << a << "  " <<b;
                
        }
        
    }
    
    else
    
    {
    
        if (a<c)
        
            cout << b << "  " << a << "  " << c;
            
        else
        
        {
        
            if ( b<c )
            
                cout << b << "  " << c << "  " <<a;
                
            else
            
                cout << c << "  " << b << "  " <<a;
                
        }
        
    }
    
    return 0;
    
}

       
# Foto Hasil


# Latihan03

Deklarasi : 

integer a,b, c

Deskripsi :

1. Masukkan (a, b, c)
2. jika (a==b && a==c)
   tampilkan("Segitiga sama sisi")
3. lainnya jika(a==b || b==c)
           jika(a!=b || a!=c)
   tampilkan("Segitiga sama kaki")
4. lainnya
   tampilkan("Segitiga sembarang")
   akhir jika

# Program C++

#include <iostream>

using namespace std;

int main()

{
   int a,b,c;

   cout<< "Masukan sisi A :";
   
   cin>> a;

   cout<< "Masukan sisi B :";
   
   cin>> b;

   cout<< "Masukan sisi C :";
   
   cin>> c;

   if (a==b && a==c)
   
   {
   
       cout<< "Segitiga Sama Sisi" << endl;
       
   }
   
   else if  (a==b || a==c)
   
   {
   
       if  (a!=b || a!=c)
       
       {
       
           cout<<"Segitiga Sama Kaki"<<endl;
           
       }
       
   }
   
   else
   
    cout<< "Segitiga Sembarang" ;
    
    return 0;
    
}

# Foto Hasil 

