# Columbia Gadget Works: bylaws and policies

The official text of CGW's bylaws and policies. The website's [policies pages](https://columbiagadgetworks.org/policies/) are built directly from this repository; there is no other copy.

**Status: ballot text.** Full members vote on these documents at the annual meeting on **Thursday 8 April 2027**. The bylaws are CGW's first; they take effect only if two-thirds of the full members voting ratify them. The board sets the policies, waiver, and member agreement; they take effect with the bylaws. The ballot is in [`ballot.md`](ballot.md); the steps before and after it are in [`policies/how-we-decide.md`](policies/how-we-decide.md).

| File | What it covers |
|---|---|
| [`ballot.md`](ballot.md) | What members vote on at each annual meeting, and who votes |
| [`bylaws.md`](bylaws.md) | The bylaws. Changed only by the members, by a two-thirds vote |
| [`policies/how-we-decide.md`](policies/how-we-decide.md) | How to propose a change and how voting works. **Start here** |
| [`policies/membership.md`](policies/membership.md) | Joining, age, dues, missed dues, guests |
| [`policies/conduct-and-safety.md`](policies/conduct-and-safety.md) | Code of conduct and shop safety |
| [`policies/conflict-and-discipline.md`](policies/conflict-and-discipline.md) | Resolving disputes, and what the board can do |
| [`policies/zones-and-roles.md`](policies/zones-and-roles.md) | Zones, Zone Bosses, Leads, and what each decides |
| [`policies/money.md`](policies/money.md) | Spending limits, zone balances, classes |
| [`policies/conflict-of-interest.md`](policies/conflict-of-interest.md) | Disclosing conflicts, and the yearly statement |
| [`policies/storage-and-donations.md`](policies/storage-and-donations.md) | Bins, project tags, the donation shelf |
| [`signup/waiver.txt`](signup/waiver.txt) | Liability waiver every member, guest, and visitor signs |
| [`signup/membership-agreement.txt`](signup/membership-agreement.txt) | Member agreement signed at signup; summarizes the policies above |
| `site.yaml` | Which files the website publishes |

## Proposing a change

Open a pull request that edits the file, or open an issue describing what you want. **Policy** changes are board votes: after 7 days for member comment, the change passes when 3 of the 5 directors approve the pull request. **Bylaw** changes and elections are member votes: they are decided by secret ballot, not on GitHub, and the pull request only holds the text being voted on. Details: [`policies/how-we-decide.md`](policies/how-we-decide.md).

## The signup documents

`signup/` holds the waiver and member agreement the online signup shows. They are plain text because the Dolibarr onboarding module displays them exactly as written. When a policy the agreement summarizes changes, update the agreement in the same pull request. Once a change is merged, paste the new text into Members > Onboarding setup in Dolibarr; everyone who signed earlier keeps a copy of exactly what they signed.

Before the first real use, a Missouri attorney should review the waiver. It follows *Alack v. Vic Tanny* (Mo. 1996), which requires a release of negligence to say "negligence" plainly and conspicuously, but no lawyer has read it yet.

## Order of authority

Missouri law (RSMo ch. 355) → Articles of Incorporation → bylaws → policies → zone rules on the wiki.
