---
layout: project
type: project
image: img/micromouse/micromouse-square.jpg
title: "Business Email Compromise"
date: 2023
published: true
labels:
  - IT Risk and Controls Management
  - Phishing

summary: ""
---

<div class="text-center p-4">
  <img width="200px" src="https://github.com/yafujimoto/yafujimoto.github.io/blob/main/img/IMG_7772.pdf" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
  
</div>

In the course of our project, we were assigned the crucial task of testing and identifying potential risks to the Bank of Hawaii concerning business email compromise. To achieve this, we initiated a simulated phishing campaign by sending deceptive emails to all 2,100 employees. Through meticulous analysis, we identified and assessed the existing controls while pinpointing significant gaps within them. Our objective was to quantify the quality of risk and gauge the bank's susceptibility to compromise. Working collaboratively with fellow interns, we meticulously compiled our findings and recommendations into a comprehensive report, which we subsequently presented to the relevant department. Our assessment revealed a high residual risk, considering factors such as probability, impact scale, and the effectiveness of the current controls, as evaluated through a rigorous rating matrix. In light of our findings, we proposed potential solutions to mitigate these identified risks and enhance the overall security posture of the Bank of Hawaii.

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
