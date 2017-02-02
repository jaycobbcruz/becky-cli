# becky-cli
A Python-based command-line interface chatbot client.

## How to use
Step 1: Install python and websocket-client
```{r, engine='bash'}
$  sudo pip install websocket-client
```

Step 2: Begin chat and enjoy!

```{r, engine='bash'}
$  python becky-cli.py 
$ hello
Becky: Hi it's great to see you!

$ my name is John
Becky: Pleased to meet you, John

$ my favorite animal is a dog
Becky: What do you like best about a dog?

$ their brains
Becky: Where are you?

$ what is my name?
Becky: John

$ what is my favorite animal?
Becky: a dog

$ what is the time in New York?
Becky: It is 10:03 A.M.

$ who is Albert Einstein?
Becky: Albert Einstein (/ˈaɪnstaɪn/; German:  ( listen); 14 March 1879 – 18 April 1955) was a German-born theoretical physicist. He developed the general theory of relativity, one of the two pillars of modern physics (alongside quantum mechanics). :274 Einstein's work is also known for its influence on the philosophy of science. Einstein is best known in popular culture for his mass–energy equivalence formula E = mc2 (which has been dubbed "the world's most famous equation"). He received the 1921 Nobel Prize in Physics "for his services to Theoretical Physics, and especially for his discovery of the law of the photoelectric effect", a pivotal step in the evolution of quantum theory.

```

## Troubleshooting
If you are receiving message "Error occurred: gaierror(8, 'nodename nor servname provided, or not known')", you will need to wake up the Heroku Dyno by visiting the web interface in https://secure-cove-19746.herokuapp.com/