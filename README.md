
Blockchain simulation with a web interface on Flask.

[Click here](https://hammoudamustaphaahmed.pythonanywhere.com) to visit the live website.

**Blockchain** –  is a continuously growing list of records, called blocks, which are linked and secured using cryptography hash. Each block typically contains a hash pointer as a link to a previous block and a timestamp. By design, blockchains are inherently resistant to modification of the data. For getting hash used _SHA-256_

### What is POW

**POW** _(proof of work)_ is a piece of data which is difficult (costly, time-consuming) to produce but easy for others to verify and which satisfies certain requirements. Producing a proof of work can be a random process with low probability so that a lot of trial and error is required on average before a valid proof of work is generated. Bitcoin uses the Hashcash proof of work system.

## How to run

```
pip install -r requirements.txt

python server.py
```

Now head over to http://127.0.0.1:5000/, and you should see main page of blockchain, where you can add new block, check blocks integrity and mined blocks using POW algorithm.


