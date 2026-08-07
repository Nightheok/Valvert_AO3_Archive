# Subject: Self-report — unauthorized public exposure of scraped AO3 works and user data, requesting remediation guidance

To the Policy & Abuse Committee,

I am writing to report, on my own initiative, a Terms of Service violation that I am responsible for, and to ask for your guidance on how best to remediate it in the interest of the affected creators and users.

What happened

I built a data-collection tool by modifying the open-source project radiolarian/AO3Scraper (adding Chinese-language compatibility, among other changes) and used it to collect a dataset of AO3 works and their metadata. I subsequently made this dataset available in a location that could be accessed publicly without logging in. I now recognize this was wrong: copying authors' work text and associated information to another publicly accessible location disregards each author's right to decide where and how their work is distributed, and creates real safety and privacy risks — particularly for Chinese-language creators. I apologize for this, sincerely and without qualification. Whatever my original purpose was, it does not excuse redistributing others' work without authorization.

Data involved

The dataset is metadata plus full work text. Based on my current review of the data:
[removed for privacy here]

The affected author and work counts above are my best current figures; I am continuing to verify them and will correct any inaccuracy promptly.

Collection method and scope (for accuracy)

The scraper ran without logging in to any account. Based on my review, the dataset does not include works restricted to logged-in users or set to be visible only to the author. The all_kudos data was collected because I enabled the tool's optional kudos-collection function; I did not adequately anticipate that this would place a large number of readers' usernames into the dataset. I am providing this technical detail only so you can assess the scope accurately.

Actions already taken

I have taken the public dataset and the associated repository offline, so they are no longer publicly accessible.
I have deleted the modified source code.
I am continuing to check for any public deployment, cache, or other residual access points (including search-engine caches and any web-archive snapshots) and will clean up whatever I find, to the extent I am able.
I have placed a clear notice at the original entry point explaining what happened, what data was involved, what measures I have taken, and that I will update it as verification and cleanup continue.

Retained verification copy

To assist your review and any remediation you advise, I am keeping a single access-restricted copy of the data solely for the purpose of verifying the scope of impact and cooperating with your instructions. It is not publicly accessible. I will delete it once it is no longer needed, or otherwise handle it as you advise.

What I am asking of you

I want to prioritize the safety of affected creators — especially Chinese-language authors — while also respecting authors' right to be informed and avoiding any secondary spread of the incident. I do not think I am the right person to individually contact hundreds of authors, comment publicly on their works, or search across platforms for their contact information: doing so could amplify the incident, cause new disturbance, and create unnecessary long-term alarm. You are in a far better position than I am to judge, from the perspective of the platform and the affected users, whether a broader notice is warranted, through what channel, by whom, and which authors — if any — should be contacted directly.

I am reporting this proactively and will provide any further factual or technical information you need. Beyond the steps above, I will follow your recommendations on how to proceed.

Thank you for your work. I can be reached at the email address associated with this report.
