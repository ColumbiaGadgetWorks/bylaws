# CGW governing documents

| File | What it is | Changed by |
|---|---|---|
| `signup/waiver.txt` | Liability waiver every member, guest, and visitor signs | Board vote |
| `signup/membership-agreement.txt` | Agreement every member signs at signup | Board vote |

The bylaws and policies draft these follow is `governance/bylaws-and-policies/bylaws-and-policies.md`
on the `bylaws-and-policies-draft` branch of CGWManagement (24 Sep 2026, not adopted).
The membership agreement summarizes Part B; when a policy changes, update the agreement in the
same pull request.

## How a change reaches the signup page

1. Edit the `.txt` file in a pull request. The pull request is the review and approval record.
2. Merge after the board approves the wording (record the vote in the minutes).
3. Tag the merge: `waiver-YYYY-MM-DD` or `agreement-YYYY-MM-DD`.
4. In Dolibarr, Members > Onboarding setup, paste the file's full text into the waiver or
   agreement box and save. Everyone who signed earlier keeps a copy of exactly what they signed;
   the module versions each wording by its content.

The files are plain text on purpose: the onboarding module shows them exactly as written.

## Before the first real use

- Have a Missouri attorney read the waiver. It follows the rule from *Alack v. Vic Tanny* (Mo.
  1996) that a release of negligence must say "negligence" plainly and conspicuously, but it has
  not been reviewed by a lawyer.
- Settle the open numbers in the policies draft that appear here: minimum age 16, the 30-day
  notice before membership ends, and the two-week penalty for leaving someone unattended.
- The online signup is for adults. A 16- or 17-year-old signs a paper waiver together with a
  parent or guardian.
