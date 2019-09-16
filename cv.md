### Junior Developer CV

##### Uladzimir Kazak
###### Contacts: 
   - mobile phone: +375 29 1090093 (A1)
   - email:  
     - mrinex@mail.ru
     - themrinex@gmail.com
   - social networks:
     - [Facebook](https://www.facebook.com/mrinex)
   - My [GitHub](https://github.com/mrINEX)
##### About me
My goal is to be a professional in what I do and what I am. I would like to be a good and valuable engineer who quickly and efficiently solves problems becouse It will lead me to success, give me further growth and I will be able to set new goals. It is important for me to become better and grow in what I do and, as I think, step by step at this stage. I am interested in everything related to development, and especially with WEB, every day I take steps towards this both in programming and in English.
###### Skills
- GitHub, Git
- VS Code
- HTML/CSS JS
- C
- VM VirtualBox
- IDEs
- SQL
###### Code examples
binary search:
```
#include <stdio.h>
#include <cs50.h>

int binarySearch(int key, int array[], int min, int max)
{
  int middle;
  if(max<min)
    return -1;
  else
    middle = (min+max)/2;
    
  if(array[middle]<key)
    return binarySearch(key, array, middle+1, max);
  else if(array[middle]>key)
    return binarySearch(key, array, min, middle-1);
  else
    return middle;
}

int main()
{
  int array[]={1, 32, 43, 54, 95};
  printf("%d\n", binarySearch(54, array, 0, 4));
}
```
###### Experience
Only is CS50 course.
###### Education
- CS50
- CodeCademy (HTML/CSS)
- Testing courses
###### English
Pre-Intermediate(A2)
My main assistant in learning English is [Puzzle English.](https://puzzle-english.com/teacher) and self education.