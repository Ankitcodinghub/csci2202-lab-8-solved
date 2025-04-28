# csci2202-lab-8-solved
**TO GET THIS SOLUTION VISIT:** [CSCI2202 Lab 8 Solved](https://www.ankitcodinghub.com/product/csci2202-1-there-are-many-ways-to-reach-fxr-0-to-find-xr-we-can-use-iteration-on-fxn-to-decide-on-the-next-approximation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116969&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI2202 Lab 8 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
– (1) • There are many ways to reach f(xr) = 0, to find xr. We can use iteration on f(xn) to decide on the next approximation:

xn+1 = F(xn) = xn − c · f(xn)

The choice of c is critical. Suppose xn converges to xr. Then, the limit of the above equation is: xr = xr − c · f(xr)

This gives f(xr) = 0! Just what we want. But, is there a perfect value for c?

Consider the linear equation f(x) = ax − b. It has a zero at xr = b/a.

Use the iteration xn+1 = xn −c(axn −b) . (Early computers could not divide.

They used such an iteration).

Subtracting xr from both sides:

xn+1 − xr = xn − xr − c(axn − b), Notice that xn − xr = en, the error in step n.

OR en+1 = (1 − c · a)en, So at every step the error is multiplied by:

(1 − c · a), which is F 0.

The error goes to zero IF |F 0| &lt; 1. i.e. the absolute value |1 − c · a| decides everything.

The Perfect Choice for c is 1/a.

Then in one iteration, we have the exact answer: x1 = x0 − (1/a)(ax0 − b) This is a linear equation – does not need calculus.

Now, for a more general f: xn+1 − xr = xn − xr − c(f(xn) − f(xr)). Here we are going to replace: (f(xn) − f(xr)) = A(xn − xr). (here xn+1 − xr ≈ (1 − cA)(xn − xr). OR en+1 = (1 − cA)en The error equation.

Once again the error will go to zero in the limit, IF |1 = cA| &lt; 1.

So now the Perfect Choice for c is

Problem We do not yet know xr.

However, we overcome that using c = 1/f0(xn). Then:

This is Newton’s Method.

• Ex. 1a Solve f(x) = 2x − cosx = 0 using iterations with different c’s. Use x0 = 0.5. Use c = 1, c = 1/f0(x0) and c = 1/f0(xn). Print x1,x2 …. side-byside columns (use 7 digits after the decimal) and use a tolerance of 1e − 7.

1

2

(Using c = 1/f0(x0) is called modified Newton’s method).

• Ex. 1b Using the xr obtained above, print three columns (for the three values of c (above)), of the error: xi − xr for i = 0,1,2…

(2) Repeat 1(d) and 1(e) for Newton’s method. Recall, for Newton’s method you need√

the derivative of the function. For√ f(x) = ln(x + 2) − x; df/dx(x) = 1/(x + 2) + 1/(2 x). Pick x0 carefully.

(3) Newton’s method is fast, but prone to problems like division by zero. We examine how Newton’s method fails: For this, solve f(x) = tanh(x) = 0 (hyperbolic Tan) (i) Start with an initial guess x0 = 1.08. Plot the tangent (and the function at each iteration of Newton’s method. (ii) Repeat with an initial guess x0 = 1.09.

Note: .

For this part, write a function to plot the curve and the tangent (like the one shown below), that you can call from your program, After each call to plot line, you will need a command input(“Hit Enter to Continue”) for the program to move to the next iteration. def plot line(f, xn, fxn, slope):

# Plot both f(x) and the tangent xf = linspace(-2,2,100) yf = f(xf) xt = linspace(xn-2, xn+2,10) yt = slope*xt + (fxn – slope*xn) # Straight line: ax + b plt.figure() plt.plot(xt, yt, ’r-’, xf, yf, ’b-’) plt.grid(’on’) plt.xlabel(’x’) plt.ylabel(’f(x)’) plt.show()

Newton’s Method: Set max number of iterations (around 40). Compute f0 = f(x0)

0 0

Compute f (x0), check that it is non-zero (if f (xk) at any stage is zero, print an error message and return None. This will terminate the execution of the function.

While |f0| &gt; tolerance and max iterations not exceeded,

Calculate

Set x0 = x1, f0 = f(x0) increase iteration count.

when loop terminates, report x1 as the approximation and the number of iteratio

3

Also print the number of function evaluations: (each time you evaluate

0

f or f = dfdx
