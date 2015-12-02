# A/B testing

If you want to answer either of the following questions, you'll need some A/B testing:

1. "Which version of our design is going to produce better results?"
2. "Is the change I'm planning to make to the product going to be effective? Will it improve the conversion rate, and should I go ahead and implement it?"

It's a popular quantitative and behavioural research tool which can help us decide between two competing alternatives. Conducting A/B test is cheap, protective and quick way to decide if a design is an improvement or not.

##What, and why?

###What can you A/B test
* Any website with a measurable goal: an e-commerce website, SaaS product signup, media website for ad clicks or subscriptions
* Basically any website with a goal to convert visitor to something else
* Text: headlines, sub-headlines, paragraphs
* Call to action (CTA) buttons
* Amount of content: short/long versions
* Different layouts
* Different checkout/signup/etc flows
* Different styles
* Pricing structures
* Promotions

###Why should you A/B test
* To get factual evidence for the success of your changes, rather than relying on intuition
* To increase conversion
* It's fairly quick and cost effective
* It's relatively risk-free: only affecting a portion of your traffic
* To minimise the risk of new design changes having a negative impact on conversion
* To uncover potential

##How to run a good A/B test

###The structure

1. Construct your starting point: a question that you want to answer. For example, _"Why is my conversion rate so low?"_
2. Do your research: use an analytics software to uncover user behaviour, interview users, send out surveys
3. Make sure you have enough traffic that your test will have statistical significance (see below)
4. Design different variants
5. Start the experiment using Google Analytics or Optimizely
6. Evaluate the results
7. Implement the winning version and look for improvement

###Statistical significance

To get accurate and statistically significant results you need to test your designs with **hundreds or even thousands** of participants. You also need to be careful about running more than one test at once: you need to be sure that the results you are recording can be attributed to the change you're testing.

Since A/B testing is usually automatised with some software such as Google Analytics or Optimizely, you should follow their suggestions and leave the test running till it says it has enough results. This will give you the confidence in the better performing version.

If you don't have the traffic, or the situation which would allow you to gain definite statistical significance, then you should take a step back and look at _qualitative_ user research techniques instead.

You can read more about statistical significance on the following pages:

* [Statistical significance & other A/B pitfalls](http://www.cennydd.com/blog/statistical-significance-other-ab-pitfalls/?s=2009/statistical-significance-other-ab-test-pitfalls/)
* [Statistical Analysis and A/B Testing](http://20bits.com/article/statistical-analysis-and-ab-testing)

###Tips and best practices

* Always test the original design so that you have a baseline.
* Always wait until the end of the experiment. Be wary of declaring a 'winner' after positive early results.
* Don't surprise your users: if you're testing a significant modification, consider sending only a portion of the traffic (5-25%) to the test.
* Intuition and gut feeling doesn't work in A/B testing. The metrics are king.
* Major modifications tend to deliver better, more dependable results than small fixes.
* Testing is a never-ending job: there is always room for improvement.

##Tools for testing

* [Optimizely](https://www.optimizely.com/)
* [Google Analytics Experiments](https://www.google.com/analytics/)
* [fivesecondtest.com](fivesecondtest.com)
  - **Five Second Test:** A Five Second Test shows your design to the tester for just five seconds. After the five seconds are up, the tester is asked a series of questions that you can specify, such as "What product do you think this company sells?", or "What was the company name?".
  - **Click Test:** A Click Test records where users click on your design. The tester is asked to follow the instructions you specify, such as "Where would you click to view your shopping cart?", or "Where would you click to choose a template for your blog?".
  - **Preference Test:** Preference Tests ask the tester to choose between two design alternatives. You can ask testers to choose based on a particular attribute (eg. "Which design looks more trustworthy?"), or simply ask them which they prefer overall.

###Interesting A/B testing case studies

* [Writing Decisions: Headline tests on the Highrise signup page](https://signalvnoise.com/posts/1525-writing-decisions-headline-tests-on-the-highrise-signup-page)
* [How two magical words increased conversion rate by 28% ](https://vwo.com/blog/ab-test-case-study-how-two-magical-words-increased-conversion-rate-by-28/)
* [A/B Test Case Study: Single Page vs. Multi-Step Checkout](http://www.getelastic.com/single-vs-two-page-checkout/)