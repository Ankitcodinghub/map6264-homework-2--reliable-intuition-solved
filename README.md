# map6264-homework-2--reliable-intuition-solved
**TO GET THIS SOLUTION VISIT:** [MAP6264 Homework 2 -Reliable Intuition? Solved](https://www.ankitcodinghub.com/product/map-6264-homework-2-reliable-intuition-20-points-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123664&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MAP6264  Homework 2 -Reliable Intuition? Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Consider a renewal process. Let X be the interrenewal times; and let I and R be the length of an interval interrupted at random and its remainder, respectively. The following BASIC simulation calculates the average values of X, I, and R (based on 10,000 replications of I and R, where T is a random interruption point).

100 FOR j=1 TO 10000 110 S=0 120 T = -1000*LOG(1-RND) 130 X= 140 c=c+1 150 SX=SX+X 160 S=S+X 170 IF S&lt;T THEN 130 180 R=S-T: I=X 190 SR=SR+R: SI=SI+I 200 NEXT j 210 PRINT SX/c,SI/10000,SR/10000

a. Run the simulation for the case when X is exponentially distributed (that is, the renewal process is a Poisson process) with E(X) = 1. Fill in the following table.

E(X) E(I) E(R)

theory simulation theory simulation theory simulation

Comment on the assertion: “It is intuitively obvious that E(I) = E(X) and E(R) = E(X) / 2.”

b. Let X = Y + u, where u is a constant (to be treated as a parameter), and Y is a random variable with probability distribution: P(Y=1) = 0.9, P(Y=11) = 0.1. Run the simulation and fill in the values indicated in the table. Calculate the theoretical values of E(I) and E(R) according to the formulas (to be derived later): E(I) = E(X) + V(X) / E(X) and E(R) = E(I) / 2.

Draw the theoretical graph of E(R) versus u. On the same graph, plot the points produced by the simulation.

Comment on the assertion: “It is intuitively obvious that as the average length of the random interval X increases (that is, as u increases), the average lengths of the interrupted interval I and its remainder R will also increase.”

E(X) E(I) E(R)

u theory simulation theory simulation theory simulation

0.0

0.5

1.0

1.5

2.0

2.5

3.0

3.5

4.0

4.5

5.0
