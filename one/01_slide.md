!SLIDE 
<script type='text/x-mathjax-config'>
  MathJax.Hub.Config({
    tex2jax: {inlineMath: [["$","$"],["\\(","\\)"]]}
  });
</script>
<script type="text/javascript"
  src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>

![UMUCLogo](umuclogo.jpg "UMUC Logo")
## Augmenting the Classroom with<br/>Web-Based Interactive Demonstrations
### James P. Howard, II

### 2014 Joint Mathematics Meeting<br/>Baltimore, Maryland<br/>17 January 2014

!SLIDE
.notes Open with a discussion of the traditional classroom.  Note the
common tools available, but also point out their limitations. 

## The Traditional Classroom

* Not Interactive
  * Blackboard and paper
  * Slow to adapt to new examples
  * Instructor is interactive...
* ...And Intelligent
  * Can provide feedback
  * Can understand student-generated problems

!SLIDE
.notes Open with a discussion of the traditional classroom.  Note the
common tools available, but also point out their limitations. 

## The Online Classroom

* Not Intelligent
  * Prepared examples
  * Limited ability to understand questions
  * Typographical limitations
* But Interactive
  * Extremely responsive
  * Can work faster than instructor

!SLIDE

## Wolfram|Alpha

* Web-based search engine
* Can understand natural language
  * "What is the mass of the moon in apples?"
    * Gives total calories as $3.673 * 10^{25}$
* Can create embeddable widgets
  * Created graphically through point-and-click
  * Does not require programming
  * Many options are configurable
  * _Requires no browser plugins_

!SLIDE

## Wolfram|Alpha Example
.notes potential examples include f(x) = 1 / (x^2 - 5x + 6) and f(x) = sin(x)

<iframe src="file/domainrange.html" width="1000" height="700" align="center"></iframe>

!SLIDE
## MathJax

* JavaScript-based math rendering
  * Converts embedded $\LaTeX$ and MathML
  * Cross-browser, renders in real time
  * If hosted, will updated automatically
  * _No plugins for browser or server_
* Can embed mathematics directly in HTML
  * Uses familiar languages
  * If MathJax fails, displays as original text

!SLIDE
## MathJax Example
   
<div style="margin: 0 auto; width: 904px; height: 500px">
  <div style="float: left; width: 450px; text-align: center;">
    <h3>Source code</h3>
    x = {-b \pm \sqrt{b^2-4ac} \over 2a}
  </div>
  <div style="float: left; width: 450px;">
    <h3>Fully Rendered</h3>
     $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}$$
  </div>
  <div style="float: left; width: 450px; text-align: center;">
    a^2 + b^2 = c^2
  </div>
  <div style="float: left; width: 450px;">
     $$a^2 + b^2 = c^2$$
  </div>
</div>

!SLIDE
## Wolfram Demonstrations

* Uses CDF, Computable Document Format
  * Display engine for mathematics
  * Based on Wolfram Mathematica
  * _Does require a browser plugin_
* Wolfram Demonstrations collection
  * More than 9000 freely-available demonstrations
  * Can be embedded into existing web pages
  * Curated list of submitted demos
    * Arranged by theme and subject matter
    * Linked to Common Core standards
  * [http://demonstrations.wolfram.com/](http://demonstrations.wolfram.com/)

!SLIDE
## Wolfram Demonstration Example

<center>
  <iframe src="file/righttriangle.html" height="700px" align="center"></iframe>
</center>

!SLIDE
## Putting it Together

* Augment the tradition classroom
  * Provide a write-up of a key topic
  * Intermingle relevant Khan Academy videos
  * Inline an interactive example
  * Use MathJax to create proper mathematics
* Goals
  * Provide additional material
  * Provide additional insight for struggling student
  * Provide a dynamic hands-on environment for learners

!SLIDE
## Acknowledgements
.notes John and Andy at UMUC, for letting me teach and providing
resources for this presentation.  The Center for Teaching and learning
for providing a Faculty Professional Development Grant to support this
presentation, and all of my College Algebra students who worked with
this and tested these.

* John Beyers, Andy Au, and Suzzane Sands
  * Leadership, Mathematics and Statistics, UMUC

<!---
* UMUC's Center for Teaching and Learning
  * Faculty Professional Development Grant
-->

* Many, many, many students
