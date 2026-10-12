# How we decide

*Policy draft. Not adopted.*

CGW makes decisions in two separate ways:

| | **Member votes** | **Board votes** |
|---|---|---|
| Decides | Who sits on the board; what the bylaws say; dissolution or merger | Everything else: all policy, the budget, appointments, discipline |
| Who votes | Every full member in good standing (not hardship or legacy members) | The five directors |
| When | The annual meeting (second Thursday of April), or a special vote | Any time |
| How | Secret ballot online. The Secretary and tellers record who voted and the totals | Reviews on a GitHub pull request, or a vote at a board meeting |
| Passes with | Quorum, then a majority (two-thirds for bylaw changes) | 3 of the 5 directors |

Zone rules are a third, smaller layer. A Zone Boss sets them on the zone's wiki page without a vote, and they must fit within policy.

If two layers conflict, the higher one wins: Missouri law, the Articles, the bylaws, policy, zone rules.

## Tools the bylaws refer to

The bylaws name these by role, so changing a tool takes a policy change, not a bylaw vote.

| Bylaws say | Today that is |
|---|---|
| Governance repository | This repository, `ColumbiaGadgetWorks/bylaws` on GitHub. Its `main` branch is the official text |
| Member chat channel | CGW's Discord server |
| Member records | Dolibarr |

## Proposing any change

Any member may propose a change to the bylaws or a policy.

1. **Open a pull request** (PR) in this repository that edits the file. The diff shows exactly what would change. If you don't use GitHub, open an issue or ask the Secretary, who will open the PR for you and credit you.
2. **Announce it.** The Secretary posts the link on Discord.
3. **Discuss it** on the PR.

A typo or formatting fix that doesn't change meaning is labeled `editorial`, and the Secretary may merge it without a vote. For the bylaws, the Secretary lists each such correction in the next member-vote notice (bylaws 5.10).

## Board votes: on GitHub

Policy changes are decided on the PR itself (bylaws 5.13).

1. **Comment period.** Members have 7 days after the Discord announcement to comment before the vote closes.
2. **Directors review the PR.** Approve means yes; "Request changes" means no. A director with a conflict of interest doesn't review.
3. **Passing.** Once 3 directors approve and the comment period is over, the Secretary merges the PR. The policy takes effect when merged, unless the PR names a later date.
4. **Confirming.** The PR and its reviews are the record. If every director in office approved, the change is final. Otherwise the board confirms it at its next meeting. If the board doesn't confirm it, the Secretary reverts it the same day.
5. **Urgent changes.** For safety or legal urgency, the board may skip the comment period if every director in office approves.

GitHub enforces this: `main` is protected, a change reaches it only through a PR with 3 approving reviews from the directors team, and approvals are dismissed when new commits are pushed, so every yes is on the final text.

Other board decisions, such as spending, appointments, and discipline, are made at board meetings and recorded in the minutes.

## Board meetings

- The board meets at least quarterly. Each regular meeting is posted on Discord at least 7 days ahead, with the agenda.
- Members may attend, except for closed sessions (bylaws 3.4).

## Member votes: by ballot

Bylaw changes and elections are not decided on GitHub. GitHub only holds the text being voted on.

1. **Getting on the ballot.** The board puts a bylaw PR to a member vote, or members petition for one (bylaws 5.3).
2. **Freezing the text.** The Secretary tags the PR's final commit `ballot/<yyyy-mm-dd>`. Members vote on that exact text.
3. **Notice.** Sent 10 to 60 days before voting opens, with a link to the tagged text and a PDF copy (bylaws 5.4).
4. **Nominations** open with the notice and close 7 days before voting opens. Any eligible member may nominate themselves, or another member who agrees. Each candidate runs for one seat only.
5. **Tellers.** With the notice, the board appoints one or two members who are not candidates as tellers.
6. **Voter roll.** On the day voting opens, the Secretary or a teller exports the list of full members in good standing from Dolibarr. The roll is kept confidential, because it shows who holds a hardship waiver.
7. **Ballot.** Online only. An online ballot service (for example Helios Voting) emails each member on the roll a personal link to a secret ballot. The notice names the service. The ballot is open at least 7 days and closes at the time stated in the notice. At the annual meeting, a laptop is set up for members who haven't voted yet. A member without email asks the Secretary or a teller for their link another way.
8. **Counting.** The service counts the ballots. The Secretary and the tellers certify the result and post it on the PR: eligible voters, ballots cast, whether quorum was met, the yes/no/abstain counts, and the outcome.
9. **Adoption.** If the vote passes, the Secretary merges the PR. If it fails, the PR is closed and kept on record.

## The annual meeting

- Held on the **second Thursday of April**, during Open Hack Night (6 pm). The ballot closes at 7 pm.
- Agenda:
  1. Treasurer's report;
  2. open floor, while the tellers certify the count;
  3. results: bylaw changes first, then elections.
- The new board appoints Zone Bosses and Leads by 30 April. Until then, everyone already in a role stays in it.

## Records

- This repository holds the only official text of the bylaws and policies. The website builds its pages directly from it.
- Every adopted change is a merged PR, and the git history is the full change record.
- Board minutes are added to `minutes/` by PR. Closed-session matters are only summarized.
- Members may inspect CGW's records as Missouri law provides.
