# AI Wedding Vows Generator

Are you feeling like you don't even know where to start with writing your wedding vows? Do you think your partner's capacity to express sentimental emotions far exceeds yours and are worried that your vows will look silly in comparison? Me too. That is why I leveraged the power of neural nets to write my vows. This project was borrowed from the work of [zthoutt](https://news.ycombinator.com/submitted?id=zthoutt)

# My vows

Andrew,
From the first day we met, the one thing I am sure of is that you are kind -- I can tell you anything without judgement. You enable me to pursue my passions, packing me dinner for those late nights in grad school, running your full first marathon as my pacer, bringing extra jackets so I don’t freeze on a ski tour and baking so many pies - (well that is as much for you as it is for me). When I decided that rather than focusing on writing my wedding vows, I was going to focus on writing an AI to write my wedding vows, naturally at first you resisted, but as you saw my excitement, you became my cheerleader once again, asking for updates on my AI, and wanting to know how training was going and what I changed about the algorithm. I don’t want to keep you waiting any longer. Here are my vows, written by an AI, curated by a human, felt from my heart.

I vow to be a partner.
I promise to nurture patiently
in all the days through our life.
I vow to nurture your dreams,
to know you are love, and not a hearth 
I will love you 
even when you don’t 
in whatever life brings. 
I will fan your adventures.
I today stand with our differences,
To share life with you and the joys.
Lastly, i love you.


# Training the Model

If you would like to train this model, you will need to use a GPU and Tensorflow 1.0. I used FloydHub with the following command:
```
floyd run <your-project-id> --gpu --env tensorflow-1.0 --mode jupyter
```

The text data can be found many places online.

