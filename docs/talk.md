<!-- .slide: data-background="#500000" class="dark" -->

# A Modal Approach to the Dynamics of Human Affect 

## T. Griffith
#### Preliminary Examination

#### May 20, 2021

---

<!-- .slide: data-background="#ffffff" class="light" -->

# 1. Motivation
# 2. Approach
# 3. Timeline


---

<!-- .slide: data-background="#ffffff" class="light" -->

# 1. Motivation

---

<!-- .slide: data-background="#ffffff" class="light" -->

# Robots that work with humans are increasingly prevalent

<img src="img/factory.jpg" alt="Trial 5, Averaged" width="32%">
<img src="img/hospital.jpg" alt="Trial 5, Averaged" width="32%">
<img src="img/army2.jpg" alt="Trial 5, Averaged" width="32%">

<div style="text-align: right"> <sub><sub><sup><a href="https://www.wired.co.uk/article/robots-in-the-workplace">Spencer Lowell</a>, Wired, 2021</sup></sup></sub></div>
<div style="text-align: right"> <sub><sub><sup><a href="https://www.flickr.com/photos/soldiersmediacenter/3966243098/in/photolist-73u2TG-dWQUxz-efXH4o-igJm3D-5q7oLi-6fqobG-dUigyC-5YRPEK-a92PNx-5YW2PN-6rGoZD-5SSAhx-4yRwME-5kS1mc-4LCHJ9">Army</a>, 2009</sup></sup></sub></div>


---

# Shared flow of information is implied

<img class="plain" src="img/arl-shared.png" alt="Trial 5, Averaged" width="60%">


<div style="text-align: right"> <small>Barnes, Michael J., Jessie Y. Chen, and Susan Hill. Humans and autonomy: Implications of shared decision making for military operations. US Army Research Laboratory Aberdeen Proving Ground United States, 2017.</small></div>


---

<!-- .slide: data-background="#ffffff" class="light" -->

# Not just performance

- Automation conundrum
- When SA is lost, [bad](https://dspace.mit.edu/handle/1721.1/70967) [things](https://sanfrancisco.cbslocal.com/2021/05/14/tesla-fatal-california-crash-fontana-was-on-autopilot-chp-says/) [happen](https://features.propublica.org/navy-uss-mccain-crash/navy-installed-touch-screen-steering-ten-sailors-paid-with-their-lives/)

![U.S.S. McCain Accident](img/mccain.jpg)




---

<!-- .slide: data-background="#ffffff" class="light" -->

## Need descriptions of human cognition and decision making as it is relevant to the ***dynamics*** of human-robot interaction.


- Rigorous
- Transparent
- Non-invasive
- Physiological

---

<!-- .slide: data-background="#ffffff" class="light" -->

# How is it done now?
<img class="plain" src="img/sota.jpg" alt="Trial 5, Averaged" width="60%">

---

<!-- .slide: data-background="#ffffff" class="light" -->

#  How is it done now?
<img class="plain" src="img/bar_rev.png" alt="Trial 5, Averaged" width="60%">

---


<!-- .slide: data-background="#ffffff" class="light" -->

# 2. Approach


---

<!-- .slide: data-background="#ffffff" class="light" -->

# Key Components of the Approach
<img class="plain" src="img/features2.jpg" alt="Trial 5, Averaged" width="60%">


---

<!-- .slide: data-background="#ffffff" class="light" -->
# 1. EEG is the measure of choice

- Lots of existing knowledge
- Widely available
- Implementation

---

<!-- .slide: data-background="#ffffff" class="light" -->
# 2. System Identification
<img class="plain" src="img/oma_svg.png" alt="Trial 5, Averaged" width="60%">

---

<!-- .slide: data-background="#ffffff" class="light" -->
# 3. State space
$x(k+1)=Ax(k)$

$y(k)=Cx(k)$ 

---

<!-- .slide: data-background="#ffffff" class="light" -->
# 4. Modal decomposition
$A=W \Lambda V$

$A=\begin{bmatrix} w_1 & w_2 &  \ldots & w_n \end{bmatrix} \begin{bmatrix} \lambda_1 & \ldots & 0 \\\ \vdots & \ddots & \vdots \\\ 0 & \ldots & \lambda_n \end{bmatrix} \begin{bmatrix} v_1^T \\\ v_2^T \\\ \vdots \\\ v_n^T \end{bmatrix}$ 

---

<!-- .slide: data-background="#ffffff" class="light" -->

# Modeling Overview
<img class="plain" src="img/overview.png" alt="Trial 5, Averaged" width="20%">


---

<!-- .slide: data-background="#ffffff" class="light" -->

<img class="plain" src="img/journal.png" alt="Trial 5, Averaged" width="50%">


---

<!-- .slide: data-background="#ffffff" class="light" -->

# Brain Modes  are Traveling and Standing
<section>
<img class="plain" src="img/animode.gif" alt="Trial 5, Averaged" style="height:600px;">
<img class="plain" src="img/compass.jpg" alt="Trial 5, Averaged" style="height:600px;">
</section>

<section>
<img class="plain" src="img/animode2.gif" alt="Trial 5, Averaged" style="height:600px;">
<img class="plain" src="img/compass2.jpg" alt="Trial 5, Averaged" style="height:600px;">
</section>

<section>
<h2> - Comparing normalized complexity plots from two output only decompositions </h4>

<img class="plain" src="img/eigenvectors.jpg" alt="Trial 5, Averaged" style="height:600px;">
</section>

---

<!-- .slide: data-background="#ffffff" class="light" -->


# Brain Modes are Physically Significant
## - An Eigenmode from 32 Channel EEG DEAP data
<img class="plain" src="img/oma1.gif" alt="Trial 5, Averaged" style="height:600px;">
<img class="plain" src="img/oma2.png" alt="Trial 5, Averaged" style="height:600px;">



---

<!-- .slide: data-background="#ffffff" class="light" -->


# Brain Modes are Interpersonally Dependent
## - Subject Identification from BW Modes (Random Forrest)
<img class="plain" src="img/confmat.jpg" alt="Trial 5, Averaged" width="80%">

---

<!-- .slide: data-background="#ffffff" class="light" -->


# Some Brain Modes are not Interpersonally Dependent
<img class="plain" src="img/commonmodes.png" alt="Trial 5, Averaged" width="40%">

<table>
  <tr>
    <td><img class="plain" src="img/common1.gif" height=480></td>
    <td><img class="plain" src="img/common2.gif" height=480></td>
  </tr>
  <tr>
    <td><sub>Subject 1: Alpha Mode 1</sub></td>
    <td><sub>Subject 2: Alpha Mode 1</sub></td>
  </tr>
 </table>



---



<!-- .slide: data-background="#ffffff" class="light" -->

# Unique Aspects of the Approach
- Online
- Robust Features
- Spatio-temporal
- Linear systems 

---

<!-- .slide: data-background="#ffffff" class="light" -->

# Assumptions and Corner Conditions
- Input is ***unknown***, persistent 
- Stationary
- Scaled
- Linear (!)


---

<!-- .slide: data-background="#ffffff" class="light" -->

# Linearity and the Brain
<img src="img/nonlinear.png" alt="Trial 5, Averaged" width="50%">

:anguished:

---

<!-- .slide: data-background="#ffffff" class="light" -->

# We Must Expect Non-Linear Effects
Leverage the model framework

<!-- .slide: data-background="#ffffff" class="light" -->

---

<!-- .slide: data-background="#ffffff" class="light" -->

# An Adaptive Modal Approach 
<img class="plain" src="img/adapt_est.png" alt="Trial 5, Averaged" width="50%">

---

<!-- .slide: data-background="#ffffff" class="light" -->

# Adaptive UIOs

<section>

<img src="img/conference.png" alt="Trial 5, Averaged" width="50%">

</section>
<section>

<h2> Input Generation </h2>

<img class="plain" src="img/zu.png" alt="Trial 5, Averaged" width="30%">
<br>
<img class="plain" src="img/zu2.png" alt="Trial 5, Averaged" width="30%">

</section>

<section>

<h2>- Toy UIO Example with Uncertain Dynamics </h2>

<img class="plain" src="img/state_error_3.png" alt="Trial 5, Averaged" style="height:600px;">
<img class="plain" src="img/input_error_4.png" alt="Trial 5, Averaged" style="height:600px;">

</section>


---

<!-- .slide: data-background="#ffffff" class="light" -->

# Adaptive UIOs for EEG
<img class="plain" src="img/UIO.jpg" alt="Trial 5, Averaged" width="95%">


---


<!-- .slide: data-background="#ffffff" class="light" -->

# 3. Timeline


---

<!-- .slide: data-background="#ffffff" class="light" -->

# Task Breakdown
- Modeling outcomes and affect
- Improve UIO fidelity
 - Develop exponential convergence rates for both input and state adaptive estimation
- Quantum extensions and decision making (stretch)


---

<!-- .slide: data-background="#ffffff" class="light" -->

## A Burst of Delight
<img src="img/curtains.jpg" alt="Trial 5, Averaged" width="40%">

---

<!-- .slide: data-background="#500000" class="light" -->

---

<!-- .slide: data-background="#ffffff" class="light" -->
## Determination of Brain Eigenmodes
### There is a Kalman Filter
- There is a Kalman filter that can recover the states
- $\hat{x}(k+1)=A\hat{x}(k)+K(k)(y(k)-C\hat{x}(k))$
 - $K(k)$ is from $P$ in the data
- Gather into a vector $\hat{X}$

---

<!-- .slide: data-background="#ffffff" class="light" -->

## Determination of Brain Eigenmodes
### Collect output data
- $H \equiv \frac{Y_p}{Y_f}=RQ^T$
- <img src="img/backup.png" alt="Trial 5, Averaged" style="height:300px;">


---

<!-- .slide: data-background="#ffffff" class="light" -->

## Determination of Brain Eigenmodes
### Project the past onto the future

- <img src="img/backup2.png" alt="Trial 5, Averaged" style="height:150px;">
- <img src="img/backup3.png" alt="Trial 5, Averaged" style="height:150px;">

---

<!-- .slide: data-background="#ffffff" class="light" -->

## Determination of Brain Eigenmodes
### Over determined LSQ problem 

- <img src="img/backup4.png" alt="Trial 5, Averaged" style="height:150px;">
- <img src="img/backup5.png" alt="Trial 5, Averaged" style="height:150px;">


---

<!-- .slide: data-background="#ffffff" class="light" -->
<section>

<h2> Backup slides: UIO </h2>

<img class="plain" src="img/backupslides/Slide6.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide7.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide8.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide9.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide10.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide11.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide12.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide13.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide14.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide15.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide16.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide17.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide33.PNG" alt="Trial 5, Averaged" width="80%">

</section>

<section>

<h2> Backup slides: UIO </h2>
<img class="plain" src="img/backupslides/Slide34.PNG" alt="Trial 5, Averaged" width="80%">

</section>















