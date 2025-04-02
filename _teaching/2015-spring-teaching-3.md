---
layout: splash
title: "Learning Julia"
permalink: /Learning Julia/
author_profile: false
code: true
---

{: .text-justify style="font-size: 16pt" reversed="reversed"}
#### Julia Programming
In this section, I would like to share my experience and sample codes from my paper, which have been simulated using Julia, with you.

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Paper: Critic Learning-Based Fault-Tolerant Control of Nonlinear Systems under a Dynamic Event-Triggered Mechanism
- <button class="btn btn--success btn--large" onclick="promptForCode('paper_event')">Download Codes</button>
  <a id="paper_event-download-link" href="https://farshad-rahimi.github.io/FarshadRahimi/files/paper_event.rar" style="display: none;" class="btn btn--success btn--large">Download Codes</a>

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Reinforcement Learning-Based Control for Nonlinear System Tracking
Here, you can download a problem of tracking for nonlinear system using RL.
- <button class="btn btn--success btn--large" onclick="promptForCode('julia_my_code')">Download Julia Codes</button>
  <a id="julia_my_code-download-link" href="https://farshad-rahimi.github.io/FarshadRahimi/files/Julia_My_code.rar" style="display: none;" class="btn btn--success btn--large">Download Julia Codes</a>

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Paper: Adaptive dynamic programming-based fault tolerant control for nonlinear time-delay systems
- <button class="btn btn--success btn--large" onclick="promptForCode('simulation_julia_adp1')">Download Julia Codes</button>
  <a id="simulation_julia_adp1-download-link" href="https://farshad-rahimi.github.io/FarshadRahimi/files/Simulation_Julia_ADP1.rar" style="display: none;" class="btn btn--success btn--large">Download Julia Codes</a>

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Paper: An online fault-tolerant control approach based on policy iteration algorithm for nonlinear time-delay systems
- <button class="btn btn--success btn--large" onclick="promptForCode('simulation')">Download Julia Codes</button>
  <a id="simulation-download-link" href="https://farshad-rahimi.github.io/FarshadRahimi/files/Simulation.rar" style="display: none;" class="btn btn--success btn--large">Download Julia Codes</a>

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Fault-Tolerant Control Approach using neural network observer
- <button class="btn btn--success btn--large" onclick="promptForCode('julia_codes_neural_observer')">Download Julia Codes</button>
  <a id="julia_codes_neural_observer-download-link" href="https://farshad-rahimi.github.io/FarshadRahimi/files/Julia_codes_Neural_observer.rar" style="display: none;" class="btn btn--success btn--large">Download Julia Codes</a>

{: .text-justify style="font-size: 16pt" reversed="reversed"}
### Optimizing Drug Administration in Cancer Therapy
Here, you can download the code of this paper.
- <button class="btn btn--success btn--large" onclick="promptForCode('final_version_codes')">Download Drug Dosing Codes</button>
  <a id="final_version_codes-download-link" href="https://farshad-rahimi.github.io/FarshadRahimi/files/Final_version_codes.rar" style="display: none;" class="btn btn--success btn--large">Download Drug Dosing Codes</a>

<script>
function promptForCode(fileId) {
    const correctCode = "Control2025"; // Set your desired code here
    const userCode = prompt("Please enter the access code to download the file:");

    if (userCode === correctCode) {
        document.getElementById(fileId + "-download-link").style.display = "inline";
    } else {
        alert("Incorrect code. Please try again.");
    }
}
</script>
