---
layout: default

---

---

<div class="mainquote">
    <b>TRiRL</b> is a half-day interdisciplinary workshop that aims to push the boundaries of our understanding of brain's ability to represent time and explore the potential benefits for reinforcement learning.
</div>

---

# About

The ability to perceive and estimate temporal dynamics can be considered as one of the central elements of intelligent biological agents – equipped with a model of their environment. Similarly, if one takes the view that an agent’s (internal) model is its primary guide to behaviour, the ability to learn appropriate temporal representations and employ them for action selection is a crucial consideration in reinforcement learning (RL).

Currently, RL agents have matured such that model-based unsupervised approaches achieve competitive and even SOTA behaviours (for instance, MuZero - _Schrittwieser et al. 2020_, or DreamerV2 - _Hafner et al. 2020_). However, these models tend to operate over a physical timescale aligned with the shift in environment dynamics. Consequently, further considerations are required to mimic the types of spatio-temporal representations observed in neuronal responses – operating at both subjective and objective (physical) timescales. Indeed, a large amount of neuroimaging and modeling studies in cognitive science have been focused on explaining temporal representations and how they influence human behaviour (using neural networks and Bayesian inference) e.g., _Jazayeri & Shadlen (2010), Roseboom et al. (2019), Deverett et al. (2019), Fountas et al. (2022)._

TRiRL will bring together experts in model-based RL and neuroscientists working on the brain's ability to represent time, in order to exchange insights, brainstorm, and encourage a multi-angle discussion on this important topic.


# Speakers

<table class="speakers">
    <tbody>                
        <tr>
            <td style="padding:2.5%;width:30%;max-width:30%">
                <img src="img/sutton.png" alt="Snow" style="width:100%">
            </td>
            <td style="padding:2.5%;width:70%;max-width:70%">
            <a href="http://www.incompleteideas.net/"><h2 style="line-height: 0.5">Richard Sutton</h2></a>
            <p style="font-size: medium;">DeepMind, Amii and University of Alberta</p>
            <h4 style="font-style:italic">"Some Foundations of Temporal Representations"</h4>
            <button type="button" class="collapsible">Abstract of the talk</button>
            <div class="content">
                <p><br>To be confirmed...</p>
            </div>
            </td>
        </tr>
    </tbody>
</table>

<table class="speakers">
    <tbody>                
        <tr>
            <td style="padding:2.5%;width:30%;max-width:30%">
                <img src="img/howard.png" alt="Snow" style="width:100%">
            </td>
            <td>
            <a href="https://sites.bu.edu/tcn/"><h2 style="line-height: 0.5">Marc Howard</h2></a>
            <p style="font-size: medium;">Boston University</p>
            <h4 style="font-style:italic">"Temporal memory in the brain and reinforcement learning"</h4>
            <button type="button" class="collapsible">Abstract of the talk</button>
            <div class="content">
                <p><br>A large body of modeling work has focused on temporal representations in memory, including working memory and episodic memory.  There is extensive evidence that neurons in a number of brain regions, including hippocampus, mPFC, lPFC and striatum, fire sequentially, forming a temporal memory of what happened when in the recent past.  More recent evidence from the entorhinal cortex shows neurons that, rather than firing sequentially, are perturbed by a stimulus and then relax back to baseline at different rates.  In the context of reinforcement learning, this population behaves as an eligibility trace, but with a spectrum of decay rates.  At a deeper level, the graded heterogeneity of decay rates lets us identify this population with the real Laplace transform of the recent past.  We propose a simple associative model to use this temporal memory to store and retrieve temporal predictions of the future.  This form of association could form the core of a new generation of RL models that take temporal representations of what happened when to predict what will happen when over an extended future.</p>
            </div>
            </td>
        </tr>
    </tbody>
</table>

<table class="speakers">
    <tbody>                
        <tr>
            <td style="padding:2.5%;width:30%;max-width:30%">
                <img src="img/momennejad.png" alt="Snow" style="width:100%">
            </td>
            <td>
            <a href="https://www.momen-nejad.org/"><h2 style="line-height: 0.5">Ida Momennejad</h2></a>
            <p style="font-size: medium;">Microsoft Research</p>
            <h4 style="font-style:italic">Temporal Abstraction in Biological and Artificial RL </h4>
            <button type="button" class="collapsible">Abstract of the talk</button>
            <div class="content">
                <p><br>Biological and artificial reinforcement learning rely on varieties of temporal abstraction. Common examples of temporal abstraction in computer science and cognitive neuroscience, among others, include associative inference (AB, BC -> AC), retrospective revaluation (ABC, BD -> AD), chunking, event segmentation, and related notions of transfer. I will first show behavioral, neural, and modeling results using RL approaches to temporal abstraction using multiscale predictive representations and varieties replay. I will then show examples of temporal abstraction, for which current approaches are insufficient, and discuss ongoing and future RL solutions to capturing temporal abstraction in brains, behavior, and machines.</p>
            </div>
            </td>
        </tr>
    </tbody>
</table>


# Schedule

| **Time**    	| **Agenda**                               	| **Details**                                                |
|-------------	|------------------------------------------	|----------------------------------------------------------- |
| 1:00 - 1:15 	| Introduction                          	| A short introduction to the topic and the workshop structure by the organisers. |
| 1:15 - 3:00 	| Keynote speakers                         	| Three keynote presentations will last approxmately 35 minutes each including questions. |
| 3:00 - 3:15 	| Break / Group allocation              	| During a coffee break, the participants will be divided into moderated groups with the aim to maintain diversity in levels of seniority and field of expertise. |
| 3:15 - 4:20 	| Group discussions                        	| All groups will be given a list of open problems in the field to discuss and propose solutions. |
| 4:25 - 4:55 	| Panel with questions 	                    | Each group will nominate representative to present the outcome of the discussion and defend the group’s position to the rest of the workshop participants, including online participants. |
| 4:55 - 5:00 	| Closing remarks                          	| In closing remarks, the results of the panel discussion will be summarised. |
|    5:00    	| Social event                             	| Participants who are physically present will be encouraged to attend a social event organised by the workshop to continue the discussion |

RLDM requires speakers and active participants to be physically present in the workshop. However, we plan to stream the whole program and we encourage online participants to submit questions online, which we will try to convey during the group and panel discussions. Finally, the most important outcomes of TRiRL will be formally described in opinion papers organised by the group moderators and written by willing participants after the workshop.

# Organisers

<div class="speakers">
    <div class="row">
        <div class="column">
            <img src="img/fountas-circle.png" alt="Snow" style="width:100%">
            <center><p style="font-size: medium;"><a href="https://www.zfountas.com">Zafeirios Fountas</a> <br> Huawei</p></center>
        </div>
        <div class="column">
            <img src="img/sajid-circle.png" alt="Forest" style="width:100%">
            <center><p style="font-size: medium;"><a href="https://ucbtns.github.io/index.html">Noor Sajid</a> <br> UCL &amp; Huawei</p></center>
        </div>
        <div class="column">
            <img src="img/zakharov-circle.png" alt="Mountains" style="width:100%">
            <center><p style="font-size: medium;"><a href="https://www.azak.cc">Alex Zakharov </a><br> Huawei</p></center>
        </div>
    </div>
    <div class="row">
        <div class="column">
            <img src="img/roseboom-circle.png" alt="Mountains" style="width:100%">
            <center><p style="font-size: medium;"><a href="https://www.warrickroseboom.com">Warrick Roseboom </a><br> University of Sussex</p></center>
        </div>
        <div class="column">
            <img src="img/tigas-circle.png" alt="Mountains" style="width:100%">
            <center><p style="font-size: medium;"><a href="https://ptigas.com/">Panagiotis Tigas </a><br> University of Oxford</p></center>
        </div>
    </div>
</div>


# Mailing list

Sign up to receive the latest updates on the event (programme announcement and livestream):

<!-- <form action="https://docs.google.com/forms/d/e/1FAIpQLScC4e6GMD69dz4qh6lKFPRQ6jjwnsC4tygrjtS5cHuloUCirw/formResponse" method="POST">
  <input style="margin-bottom:3px;" type="text" jsname="YPqjbf" tabindex="0" placeholder="Email address*" required>
  <center><button type="submit" class="btn-form">Send</button></center>
</form> -->

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLScC4e6GMD69dz4qh6lKFPRQ6jjwnsC4tygrjtS5cHuloUCirw/viewform?embedded=true" class="google-form" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

<!-- <input type="email" class="whsOnd zHQkBf" jsname="YPqjbf" autocomplete="email" tabindex="0" aria-label="Your email" required="" dir="auto" data-initial-dir="auto" data-initial-value=""> -->

<!-- <table class="speakers">
    <tbody>               
        <tr>
            <td style="padding:2.5%;width:15%;max-width:15%">
                <a href="https://www.zfountas.com"><img style="width:100%;max-width:100%" alt="profile photo" src="img/fountas-circle.png" class="hoverZoomLink"></a>
                <center><p style="font-size: medium;"><a href="https://www.zfountas.com">Zafeirios Fountas</a> <br> Huawei</p></center>
            </td>
            <td style="padding:2.5%;width:15%;max-width:15%">
                <a href="https://ucbtns.github.io/index.html"><img style="width:100%;max-width:100%" alt="profile photo" src="img/sajid-circle.png" class="hoverZoomLink"></a>
                <center><p style="font-size: medium;"><a href="https://ucbtns.github.io/index.html">Noor Sajid</a> <br> UCL &amp; Huawei</p></center>
            </td>
            <td style="padding:2.5%;width:15%;max-width:15%">
                <a href="https://www.azak.cc"><img style="width:100%;max-width:100%" alt="profile photo" src="img/zakharov-circle.png" class="hoverZoomLink"></a>
                <center><p style="font-size: medium;"><a href="https://www.azak.cc">Alex Zakharov </a><br> Huawei</p></center>
            </td>
            <td style="padding:2.5%;width:15%;max-width:15%">
                <a href="https://www.warrickroseboom.com"><img style="width:100%;max-width:100%" alt="profile photo" src="img/roseboom-circle.png" class="hoverZoomLink"></a>
                <center><p style="font-size: medium;"><a href="https://www.warrickroseboom.com">Warrick Roseboom </a><br> University of Sussex</p></center>
            </td>
        </tr>
    </tbody>
</table> -->



# References

1. Deverett, B., Faulkner, R., Fortunato, M., Wayne, G. & Leibo, J. Z. (2019), ‘Interval timing in deep reinforcement learning agents’, Advances in Neural Information Processing Systems 32.
2. Fountas, Z., Sylaidi, A., Nikiforou, K., Seth, A. K., Shanahan, M. & Roseboom, W. (2022), ‘A predictive processing model of episodic memory and time perception’, (in press) Neural Computation.
3. Hafner, D., Lillicrap, T., Fischer, I., Villegas, R., Ha, D., Lee, H. & Davidson, J. (2019), Learning latent dynamics for planning from pixels, in ‘International conference on machine learning’, PMLR, pp. 2555–2565.
4. Jazayeri, M. & Shadlen, M. N. (2010), ‘Temporal context calibrates interval timing’, Nature neuro- science 13(8), 1020–1026.
5. Roseboom, W., Fountas, Z., Nikiforou, K., Bhowmik, D., Shanahan, M. & Seth, A. K. (2019), ‘Activity in perceptual classification networks as a basis for human subjective time perception’, Nature communications 10(1), 1–9.


<script>
    var coll = document.getElementsByClassName("collapsible");
    var i;

    for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
        this.classList.toggle("active");
        var content = this.nextElementSibling;
        if (content.style.maxHeight){
        content.style.maxHeight = null;
        } else {
        content.style.maxHeight = content.scrollHeight + "px";
        }
    });
    }
</script>
