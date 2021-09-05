# Yemi Runsewe
## Favourite Place/ Loctaion: France, Paris

I choose Paris as my favourite place because it is know for it's **pasteries** and i **love** baking.

---

## Directions to France
1. Take a bus or Drive to Kansas City International Airport
    1. Drive form maryville to KCI is about an hour and fifteen minutes
1. Take an flight on any international aircraft to Paris CDG
    1. Check in luggage
    1. Get boardng pass
    1. Go through TSA
    1. Board flight

## Items that should be taken on journey
* Id
* Smart phone or a camera
* Money

My [About Me Page](AboutMe.md)

---

## Food and Drinks Recommendations

I have added some of my favorite foods, location and the prices in the table below

| Food/drink | Location | Price |
| ---| ---| ---: |
| Korean Hotdogs | machi machi, nyc  | 5 |
| Naked pinacolada | Walmart or most Grocery store | 6.25 |
| Chicken Alfredo Pasta | Olive Garden or Cheesecake Factory | 5.99 |
| Black milk tea with Boba | Any Bubble tea store | 6.25 |

---
## Pithy Quotes

>"The way is see it if you want the rainbow, you gotta put up with the rain" - ***Dolly Parton***

>"Many of life's failure are people who did not realize how close they were to sucess when they gave up" - ***Thomas A. Edison***

---

## Code Fencing

>A Randomized meldable heap is a priority queue based data structure in which the underlying structure is also a heap-oriented binary tree. However there are no restrictions on the shape of the underlying binary tree 

Source [Link to Description](https://en.wikipedia.org/wiki/Randomized_meldable_heap)


```
Tree* merge(Tree* t1, Tree* t2) {
    if (!t1 || !t2)
        return t1 ? t1 : t2;
    if (t2->value < t1->value)
        swap(t1, t2);
    if (rand() & 1)
        swap(t1->l, t1->r);
    t1->l = merge(t1->l, t2);
    return t1;
}
```
Source [Link to Description](https://cp-algorithms.com/data_structures/randomized_heap.html)