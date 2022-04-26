# cplus-project-for-beginners2



#include<iostream>
#using namespace std;

main()
{
   int birinci=0,ikinci=1;
   int sonraki,c,sayi;
   cout <<"kac adet fibonacci serisi oluscak"<<endl;
   cin>>sayi;
   cout<<sayi<<" adet fibonacci serisi olsutu"<<endl;

   for(c=0;c<sayi;c++)
   {
       if(c<=1)
       {
           sonraki=c;
       }
       else
       {
           sonraki=birinci+ikinci;
           birinci=ikinci;
           ikinci=sonraki;
       }
       cout<<sonraki<<" ";
   }
   cout<<endl;



   return 0;
}
