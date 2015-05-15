# Etched In Stone

Anthropologists have found stone carvings with pre-historic writing in an excellent state of
preservation. Modern data unfortunately is not as resilient! Data loss or corruption happens,
due to a variety of reasons - power outages, disks going bad, etc.

This kata is about having a plan B. How do you ensure that your database is backed up at regular intervals?

Think about factors like:
- How often do you take backups?
- Where are backups stored - no point storing them on the same disk as the data, right?!
- Can backups be quickly and easily restored?
- Is the backup process automated?
- Do you have confidence that the backups you generate are valid?
- Are there different strategies for relational v/s NoSQL DBs?
- What if your DB is distributed with eventual consistency - where do you take backups from?

Remember, that these questions are intended to serve as guide posts. You may want to get started
with attacking the simple problems first, and as you gain confidence, think about the harder problems.

The goal of kata is not to get things done in a rush, but to contemplate the 'why' of things. So,
take your time, and enjoy yourself.
