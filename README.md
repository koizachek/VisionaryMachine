# VisionaryMachine: Can GPT-4. -3.5 or -3 generate plausible future scenarios?

## In this research project, I tested and analyzed three future scenario generation methods, based on a GPT-3 finetuned davinci, GPT-3.5 prompt-tuned text-davinci-003 and a five-shot prompted GPT-4

Dedicated as my Master's Thesis at Freie University of Berlin, the >>Visionary Machine<< aims to produce authentic future scenarios, based on a dataset of scraped human-made scenarios from recognized public institutions concerning the years 2030, 2040 and 2050. The repository makes most sense in this order:

0) requirements.txt
1) code: contains all steps and descriptions how to re-create the experiment
2) data: contains the raw data and the sources
3) analysis: contains the content analysis of the future scenarios
4) fine-tune: contains a descritopn and json file to fine-tune your own model
5) prompt-tune: contains a documentation of prompt-tuning parameters and output
6) scenarios: contains the final four data sets
7) soon: data anaylsis from foresight expert survey

## What are Scenarios?

No future research methods represent discipline as much as scenario methods. The development of possible future worlds and the description of the way to them provide the basis for decision-making and at the same time space for speculation. The result is described in scenic texts and makes the future narrative, desirable or warns of it: the so-called scenarios. Not least because of the pandemic, possible futures have found their way into the reality of a critical mass - the population received forecasts every day, while economic, political and civil actors speculated about post-pandemic future scenarios. In the course of this, the creation and publication of future scenarios achieved a wide range: A resource of over 1060 human-written scenarios was scraped, parsed and translated into english, forming a data set to fine-tune GPT-3 on.

## How did I work with the Scenarios? My four data sets of scenarios consist of:

1) +1.000 Human-made scenarios were scraped, cleaned, summaried and analyzed to use them for the fine-tuning of GPT-3. 
2) The fine-tuned model generated 1.000 scenarios as well, based on the keywords deriving from the human-made scenarios. 
3) Then I prompt-tuned GPT-3.5 text-davinci-003 on the same keywords and tested the most creative parameter settings with a small panel of experts, to then generate +1000 scenarios with the global settings. 
4) Lastly, I used five-shot prompting for GPT-4 to generate a fourth dataset of +1.000 scenarios.

## My research question aims to assess the possibility of automatically generating “authentic” scenarios with the help of artificial intelligence.

<a href="https://ibb.co/CmHRP2p"><img src="https://i.ibb.co/mbcfN8r/Bildschirm-foto-2023-03-27-um-19-52-29.png" alt="Bildschirm-foto-2023-03-27-um-19-52-29" border="0"></a>

In case authenticity and human-likeness in terms of output is possible: What would AI “imagine”? Is it even able to generate other content than the scenarios that humans have developed prior? And if so, what is the differences between machine-imaginaries and human-made futures? 


Update 28.03.2023: E-Delphi Survey started

Update 05.04.2023: E-Delphi Survey ended
