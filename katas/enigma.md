# Enigma

[Enigma](http://en.wikipedia.org/wiki/Cryptanalysis_of_the_Enigma) is the name of
the machine that allowed the Germans to encrypt their radio messages during the
Second World War. Alan Turing's work on breaking the Enigma cipher is considered
to have played a crucial role in the Allies winning the war.

In today's world of SaaS applications, with consumer keys and secrets, you are faced with the constant threat of your keys being discovered and your systems being hacked.

This kata is about protecting your secrets - such as service credentials, database
passwords, etc. For example, if you use Stripe to process payments, you don't
store credit card details. But you do store tokens that identify the card on Stripe.
What if your tokens and Stripe API key got stolen? It is almost as bad as losing
the credit cards themselves.

So, how do you keep your secrets *secret*? Here are a few questions to guide you:
- Where do your secrets live? Who can see them?
- Are your secrets in source control? Is that a risk?
- Is your archived data encrypted?
- Are you using the right kind of encryption - think of the tradeoffs of various
encryption algorithms available and which is the right one for the right task.
- Does your encryption algorithm have an impact on performance - is the tradeoff worth it?
- Do you need encryption or can you do a one way transform - for e.g. for storing
passwords.
- Are your secrets ephemeral or persistent on your systems - for e.g. environment
variables are scoped to the lifetime of the shell, while files live for ever.

Remember, that these questions are intended to serve as guide posts. You may want to get started
with attacking the simple problems first, and as you gain confidence, think about the harder problems.

The goal of kata is not to get things done in a rush, but to contemplate the 'why' of things. So,
take your time, and enjoy yourself.
