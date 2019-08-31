# Bitcoin-Transaction-Legality

* In this task, I wanted to classify bitcoin transactions as licit or illicit. Thus I have proposed the
way to detect malicious transactions.

* This problem was chosen because the Elliptic Data Set maps Bitcoin transactions to real entities
belonging to licit categories (exchanges, wallet providers, miners, licit services, etc.) versus illicit
ones (scams, malware, terrorist organizations, ransomware, Ponzi schemes, etc.). This will help
us identify whether a person should continue or not with the given transaction. This prototype
can be exposed as an API and can be used by cryptocurrency wallets to protect its users from
malware and scams.

* For this task I have used the dataset given above with 166 anonymized features collected from
real transactions. Then I used binary classifiers to categorize such transactions.

* More information and links to the dataset can be found in the **docs** folder.
