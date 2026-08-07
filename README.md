Hi, I'm Danut. London. Cyber security degree, then IT at a London estate agency
group (helpdesk to security in about seven months), now trading full-time and
building the automation around it.

Two things worth looking at:

**[order-recon](https://github.com/dmnitro/order-recon)** – reconciles three
systems that disagree about the same orders (shop platform, warehouse, carrier),
checks carrier invoices against the rate card, and drafts the chase emails.
Nothing gets sent until a person approves it. There's a selftest that plants
faults in the data and fails unless every single one is found. No dependencies
beyond Python.

**[prompt2png](https://github.com/dmnitro/prompt2png)** – renders long text
prompts to PNG because image tokens are priced by area, not content. 53% cheaper
on long prose, worse on short prompts and code. The README has the numbers
either way.

Most of what I build has the same shape: the boring part runs on a schedule,
a person signs off anything that leaves the machine.

[LinkedIn](https://www.linkedin.com/in/danut-minecan-88bb02219)
