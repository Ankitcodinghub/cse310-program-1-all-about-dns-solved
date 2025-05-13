# cse310-program-1-all-about-dns-solved
**TO GET THIS SOLUTION VISIT:** [CSE310 Program 1-All about DNS Solved](https://www.ankitcodinghub.com/product/cse310-program-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93849&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE310 Program 1-All about DNS Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

Almost everything on the Internet involves DNS resolution. If DNS is slow, the performance of your application is going to suffer. The goal of this homework is write your own DNS resolver, and compare its performance with other existing DNS resolvers.

You can assume that you have access to a

<ol>
<li>You can access the IP address of the root servers from https://www.iana.org/domains/root/servers.</li>
<li>Build a “dig”-like tool called “mydig”. The mydig tool takes as input the name of the domain you want to resolve. You should resolve the “A” record for the query.When run as “mydig www.cnn.com”, your tool should display the followingQUESTION SECTION: www.cnn.com. IN A
ANSWER SECTION:

www.cnn.com. 262 IN A 151.101.209.67

<pre>         Query time: How much time it took to resolve the query
         WHEN: Data and time of request
</pre>
</li>
</ol>
You will use two APIs to create a DNS request to each individual server. The first is to create a DNS query and the second is to send this query to the destination. Figuring out the right APIs is up to you, but both can be found in the library.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
Part A

You will be implementing a DNS resolver. The resolver takes as input a domain name. Your resolver resolves this query by first contacting the root server, the top-level domain, all the way until the authoritative name server.

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
library that can resolve a single iterative DNS

</div>
</div>
<div class="layoutArea">
<div class="column">
query. The set of libraries that you may use are given in the Appendix. The libraries also

</div>
</div>
<div class="layoutArea">
<div class="column">
perform complete DNS resolution, but you are *not* allowed to use that.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Along with the code, you need to submit an output file called “mydig_output”, that

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
contains the expected output for running your mydig program. Please specify the input

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
to your program.

In some cases, you will not be able to resolve the query to the complete IP address, but only get a “CNAME”. In this case, simply output the CNAME in the answer section.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 2">
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Bonus (5%): In some cases, you may need additional resolution. For example,

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
google.co.jp will often not resolve to an IP address in one pass and will resolve to a

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
CNAME. For bonus points, you can handle this case.

PART B

Your next task is to measure the performance of your DNS resolver from Part A. Pick 10 out of the top 25 Websites from alexa.com (http://www.alexa.com/topsites.)

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Experiment 1: Run your DNS resolver on each website 10 times and find the average time, 25th percentile, and 75th percentile to resolve the DNS for each of the 25 websites.

Experiment 2: Now use your local DNS resolver and repeat the experiment(call this Local DNS). Find the average time to resolve the address for the 10 websites.

Experiment 3: Change the DNS resolver to Google’s public DNS (The IP address of this public DNS is often 8.8.8.8, or 8.8.4.4, but you need to verify). Repeat the experiment one more time and call this result “Google DNS”

You can use the dig command for experiments 2 and 3.

For each of the 10 Website, plot the average, 25th percentile and 75th percentile values over the 10 runs and draw a graph. The x axis is the website, named 1 to 10. The y axis is the time taken to resolve the query. Each point will have three bars corresponding to the three experiments. The 25th and 75th percentile should be shown as a box plot.

Explain your result as best as you can.

Submission instruction

You need to submit your homework in a single zip file as follows:

<ul>
<li>The zip file and (the root folder inside) should be named using your last name, first name, and the assignment name, all separated by a dash (‘-‘)

e.g. lastname-firstname-assignment1.zip</li>
<li>The zip file should contain your code corresponding to Part A and your answer in Part B. Please be sure to put code in the root folder rather than in separate folders. Provide sufficient comments to your code.</li>
<li>Include the expected output file “mydig_output” as specified in Part A.</li>
<li>You should provide a README file describing:◦ External libraries used.

◦ Instructions on how to run your programs.All README and your answer to Part B should be in pdf.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
APPENDIX

A. You may write your programs in Python. You can use the DNS library to perform the single DNS resolution. The recommended library is:

python —&gt; dnspython

You will likely need to install this library on python. If you choose to write your program using any other language or using a different DNS library, you should get permission from the instructor first. Remember that you cannot use these libraries to perform the entire resolution.

A note on running your code using the Universities network

If you are not able to connect to the root servers on campus, this is because the campus network blocks access to the root servers (but the CS department network does not do so). You can work around this by using a VPN. Please note that TunnelBear VPN does not work. It resolves the complete query for you even if you are trying to do it iteratively.

</div>
</div>
</div>
