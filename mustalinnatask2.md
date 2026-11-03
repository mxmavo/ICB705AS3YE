# MUSTA LINNA

## h2 Scene / Cyber moves fast

a) EP 182: Blackshades

That podcast is about Blackshades, a remote access trojan virus that was sold on hacker forums and in the dark web for a relatively low price around $40 on average making hundreds of thousands of dollars for its creators. According to intelligence estimates, more than 500000 computers worldwide were infected.

I think its success was largely based on social engineering and tricking people. In my opinion, humans are quite easy to manipulate by nature, partly because of how our brains have evolved. We are naturally curious, tend to trust things that look familiar, react emotionally, and often make quick decisions without thinking about the possible risks. Hackers know how to exploit these human weaknesses. Sometimes it is much easier to trick a person than to break through technical security.

A total of 97 people were arrested, almost all of them men. Interesting, I had completely forgotten about this. I actually switched to Mac in 2010, so I definitely could not have been infected. To stop that virus was described as one of the largest global cyber operation in history was conducted to stop the people behind this RAT virus.

b) https://www.schneier.com/blog/archives/2026/10/hiding-capabilities-in-ai-models.html
https://arxiv.org/abs/2610.13928

Hiding Capabilities in AI Models

Source: Bruce Schneier’s blog, 27 October 2026. It points to the arXiv paper “AI Models Can Provably Hide Arbitrary Capabilities” by Andis Draguns, Sumeet Ramesh Motwani, Raymond Douglas, Christian Schroeder de Witt


Before a company releases an AI model, it tests the model for dangerous skills. These tests only work if every hidden skill can be found. The authors show this idea fails when an attacker is involved. 
arxiv

What they did:

1) They built backdoor attacks that put an encrypted neural network inside the weights of a normal model. The hidden network is decrypted and run only when it gets a secret trigger. (Weights are the numbers inside an AI model that store what it has learned. A model has billions of them, and you cannot read them like normal code)

2) Because of the encryption, the hidden part is very hard to find or understand, even when you can see all the model weights. 

3)They tested it with a small chemistry task. It stands in for dangerous CBRN (chemical, biological, radiological, nuclear) knowledge. Normal ways to find hidden skills did not work. These included fine-tuning, adding noise to weights, searching for the trigger, and adversarial training. 

So here comes the outcome if a model passes a safety test, that does not prove it is safe. A bad actor can hide a skill so good that testing cannot find it. So who made the model and where you got it matters a lot, worth checking always.


c) Science that



## REFERENCES

- Schneier, B. (2026). Hiding Capabilities in AI Models. https://www.schneier.com/blog/archives/2026/10/hiding-capabilities-in-ai-models.html

-Draguns, A., Motwani, S. R., Douglas, R., Schroeder de Witt, C. (2026). AI Models Can Provably Hide Arbitrary Capabilities. arXiv:2610.13928. 
https://arxiv.org/pdf/2610.13928

-My h1: https://github.com/mxmavo/ICB705AS3YE/blob/main/mustalinnah2.md
