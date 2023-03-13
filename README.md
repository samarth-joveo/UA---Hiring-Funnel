# UA Hiring Funnel
![image](https://user-images.githubusercontent.com/104884127/224622392-d64a56e5-d84b-44b1-844b-b4efc9debd15.png)
</br>Flow of Data : Dynamic number of columns based on the requirement.
</br>Assumption : The flow of data will always be from higher to lower. First column will be clicks, then apply starts etc. 
</br>Ideal Implementation : Assume that number of columns might change and make the visual dynamic enough to handle any changes. 
Data from Looker : 
![image](https://user-images.githubusercontent.com/104884127/224623415-50213069-e5f9-4a86-9a79-aad9440c7a82.png)
Format of the data flowing to looker visual : 
</br>data = [</br>
  { 'clicks':{ 'value' : '1000' } , 'apply_start' : { 'value' : 100 } , 'applies' : { 'value' : 10 }, 'hires' : { 'value' : 1 }   }
</br>]
