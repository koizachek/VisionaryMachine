# VisionaryMachine
A Future Scenario Generator, based on a finetuned GPT-3.5, Davinci-003


Hello, there!

Welcome to this project: Originally dedicated as my Master's Thesis at Freie University of Berlin, the >>Visionary Machine<< aims to produce authentic future scenarios, based on a synthetic dataset created with vanilla GPT-3 and an equal-in-size human-made scenario dataset concerning the years 2030, 2040 and 2050. Both datasets consist of 1056 scenarios. 

What are Scenarios?

No future research methods represent discipline as much as scenario methods. The development of possible future worlds and the description of the way to them provide the basis for decision-making and at the same time space for speculation. The result is described in scenic texts and makes the future narrative, desirable or warns of it: the so-called scenarios. Not least because of the pandemic, possible futures have found their way into the reality of a critical mass - the population received forecasts every day, while economic, political and civil actors speculated about post-pandemic future scenarios. In the course of this, the creation and publication of future scenarios achieved a wide range: A resource of over 1060 human-written scenarios was scraped, parsed and translated into english, forming a data set to fine-tune GPT-3 on.

How did I work with the Scenarios?

The scenarios were analyzed with DistilBERT-uncased-emotions before they become (or more specifically, I made them to) the database for the fine-tuning of GPT3.5's Davinci-003 Engine (trying the best model) and Ada Engine (trying the most creative model). My research question deals with the possibility of automatically generating “authentic” visions of the future with the help of artificial intelligence. Text processing is one of the strengths of Narrow Artificial Intelligence, which is very well possible based on current state of the art. 

Why?

From the scenarios generated, I expect to gain insights into the language we use, when foresight experts talk about the future. Using Methods like Sentiment Analysis and Topic Distribution reveals patterns and quantifies previously uncounted things. 

The Fine-Tuning on the other hand should, as I work with a high model temperature (making the model less deterministic), reveal machine-made futures that are analyzed with the same means. This brings content motifs to the surface, connections and clusters are shown. The parameters with which algorithmic models operate are also an important basis for the traceability of the AI. If an algorithm can create images of the future, what would it “imagine”? And is it able to generate other content than the scenarios that the person has developed? Publicly accessible language models refer to various training data from the Internet. 

With these two synthetic datasets on scenarios, I aim to build the foundation of a comparison between human and machine-futures. 

What could it look like?

<img width="454" alt="grafik" src="https://user-images.githubusercontent.com/85067527/144433365-b5f64754-f82b-414e-a911-762f8ef983f1.png">

A first test run with the opensoource model GPT-Neo reveals the the “imagination” of the AI: Even small changes such as punctuation marks or additional spaces generate images of the future that have little to do with human futures and at the same time make the results opaque and difficult to reconstruct. 

I hope this project will show something slightly more authentic – I will post updates on the project here.
