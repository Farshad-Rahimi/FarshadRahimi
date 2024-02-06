---
layout: splash
title: "Programming Codes"
permalink: /Programming Codes/
author_profile: false
code: true
---


{: .text-justify style="font-size: 16pt" reversed="reversed"}
#### Codes


{: .text-justify style="font-size: 12pt" reversed="reversed"}
**Rahimi, F.**, Sh. Ahmadpour, [Neighborhood-Based Distributed Robust Unknown Input Observer for Fault Estimation in Nonlinear Networked Systems](https://ietresearch.onlinelibrary.wiley.com/doi/full/10.1049/cth2.12278){:style="color: blue"}. *IET Control Theory & Applications* 16.10 (2022): 972-984.
{: .text-justify style="font-size: 16pt" reversed="reversed"}
Here are my Matlab files for the paper we recently published in IET Control Theory and Applications. \\
We need the following steps:\\
Yalmip Toolbox must be added to Matlab.\\
https://yalmip.github.io/download/\\
How to Install a MATLAB toolbox?\\
https://www.osc.edu/resources/getting_started/howto/howto_install_a_matlab_toolbox\\
After that, you can run the attached codes. 
- [Matlab_Codes](/files/CodeprogrammingMatlab_example2_2.rar){:id="programming-codes-download" data-code="true"}
$(document).ready(function() {
    // ... (your existing code)

    // Add the code for Password-Protected download
    $("#programming-codes-download").on("click", function() {
        downloadProgrammingCodes();
    });
});

function downloadProgrammingCodes() {
    var codesSection = getCodesSection();
    
    if (codesSection && codesSection.code) {
        var enteredCode = prompt("Enter the authentication code: 2446");

        if (enteredCode === "your_secret_code") {
            window.location.href = codesSection.url;
        } else {
            alert("Invalid code. Access denied.");
        }
    } else {
        window.location.href = codesSection.url;
    }
}

function getCodesSection() {
    // Adapt this function based on your actual HTML structure
    var codesLinkElement = $("#programming-codes-download");

    if (codesLinkElement.length > 0) {
        return {
            title: "Programming Codes",
            url: codesLinkElement.attr('href'),
            code: codesLinkElement.data('code') === true
        };
    } else {
        // Handle the case where the Programming Codes link is not found
        console.error("Programming Codes link not found.");
        return null;
    }
}




