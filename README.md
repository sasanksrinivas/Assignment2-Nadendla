# Assignment2-Nadendla
# Sasank Srinivas Nadendla
###### AKF
It is located near **Spensers**
And it is famouse for food
It is a very big restaurant
We can find Indian special dosa in **DosaArt** to near AKF

***

## Airport to AKF

The airport that is close to spensers is Indira International airport
1.Book a cab to Ameerpet
2.from Ameerpet take a auto to kukatpally
3.walk 150 meters east to reach AKF which is quite opposite to Spenser

I recommend the following food list
* Cup Cakes
* Noodles
* walnuts
* moisturizers</br>
[About me](AboutMe.md)

***
#### Physical Activities</br>
The table indicates the sports name, location and it's price in dollors

| Name |  Location | Amount |
| --- | --- | ---: |
| TableTennis | Rec | 4 |
| Badminton | Colden | 5 |
| Squash | Rec | 6 |
| Cricket | Parking Area | 10 |

***
### Quotes
>“Cowards die many times before their deaths; The valiant never taste of death but once.”</br>
  -*Julius Caesar*</br>
>"Good night, good night! Parting is such sweet sorrow,
 That I shall say good night till it be morrow.”</br>
-*Romeo and Juliet*

***

### Code Fencing
>An ancient method which appeared about 200 BC in Pingala's Hindu classic Chandah-sutra (and now called left-to-right binary exponentiation) can be described as follows. First write the exponent 25 in binary: 11001. Remove the first binary digit leaving 1001 and then replace each remaining '1' with the pair of letters 'sx' and each '0' with the letter 's' to get: sx s s sx. Now interpret 's' to mean square, and 'x' to mean multiply by x, so we have:

square, multiply by x, square, square, square, multiply by x.. [description]<https://primes.utm.edu/glossary/page.php?sort=BinaryExponentiation>

```
long long binpow(long long a, long long b) {
    if (b == 0)
        return 1;
    long long res = binpow(a, b / 2);
    if (b % 2)
        return res * res * a;
    else
        return res * res;
}

```
[description]<https://cp-algorithms.com/algebra/binary-exp.html>