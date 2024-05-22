## 2024 Question 1
# a)
The comments were intentionally left as they are

```
public void simulateOneDay(int numBirds)
{ /* to be implemented in part (a) */ 

eat_day = Math.random()*40+10;
bear_comming = Math.random();
if(currentFood>eat_day && bear_comming>=0.95){
  currentFood = currentFood-eat_day;
}else{
  currentFood = 0;
}


}
```
# b)

```
public int simulateManyDays(int numBirds, int numDays)
{ /* to be implemented in part (b) */ 
for(int i=0; i<=numDays; i++){
  simulateOneDay(numBirds);
}
  return numDays;

}
```
