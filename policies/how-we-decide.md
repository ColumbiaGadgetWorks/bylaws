# How we decide

*Policy draft. Not adopted.*

CGW makes decisions in two separate ways:

| | **Member votes** | **Board votes** |
|---|---|---|
| Decides | Who sits on the board; what the bylaws say; dissolution or merger | Everything else: all policy, the budget, appointments, discipline |
| Who votes | Every member in good standing | The five directors |
| When | The annual meeting (second Thursday of April), or a special vote | Any time |
| How | Secret ballot. The Secretary records the votes (method below) | Reviews on a GitHub pull request, or a vote at a board meeting |
| Passes with | Quorum, then a majority (two-thirds for bylaw changes) | A majority of directors |

Zone rules are a third, smaller layer. A Zone Boss sets them on the zone's wiki page without a vote, and they must fit within policy.

If two layers conflict, the higher one wins: Missouri law, the Articles, the bylaws, policy, zone rules.

## Proposing any change

Any member may propose a change to the bylaws or a policy.

1. **Open a pull request** (PR) in this repository that edits the file. The diff shows exactly what would change. If you don't use GitHub, open an issue or ask the Secretary, who will open the PR for you and credit you.
2. **Announce it.** The Secretary posts the link on Discord.
3. **Discuss it** on the PR.

A typo or formatting fix that doesn't change meaning is labeled `editorial`, and the Secretary may merge it without a vote.

## Board votes: on GitHub

Policy changes are decided on the PR itself.

1. **Comment period.** Members have 7 days after the Discord announcement to comment before the vote closes.
2. **Directors review the PR.** Approve means yes; "Request changes" means no.
3. **Passing.** Once a majority of directors (3 of 5) approve and the comment period is over, the Secretary merges the PR. The policy takes effect when merged, unless the PR says otherwise.
4. **Record.** The PR and its reviews are the record. At the next board meeting, the board confirms every policy change merged since the last meeting (bylaws 5.12).
5. **Urgent changes.** For safety or legal urgency, the board may skip the comment period if all five directors approve.

Other board decisions, such as spending, appointments, and discipline, are made at board meetings and recorded in the minutes.

## Member votes: by ballot

Bylaw changes and elections are not decided on GitHub. GitHub only holds the text being voted on.

1. **Getting on the ballot.** The board puts a bylaw PR to a member vote, or members petition for one (bylaws 5.3).
2. **Freezing the text.** The Secretary tags the PR's final commit `ballot/<yyyy-mm-dd>`. Members vote on that exact text.
3. **Notice.** Sent by email 10 to 60 days before voting opens, with a link to the tagged text and a PDF copy (bylaws 5.4).
4. **Nominations** open with the notice and close 7 days before voting opens. Any eligible member may nominate themselves, or another member who agrees.
5. **Voter roll.** On the day voting opens, the Secretary exports the list of members in good standing from Dolibarr.
6. **Ballot.** Secret ballot, open at least 7 days, closing at the end of the meeting. Voting method: **[to be decided]**. Options under consideration:
   - an online ballot service that emails each member a personal link (such as Helios Voting);
   - paper ballots at the meeting.
7. **Counting.** The Secretary counts the votes and a second director checks the count. The Secretary posts the result on the PR: eligible voters, ballots cast, whether quorum was met, the yes/no/abstain counts, and the outcome.
8. **Adoption.** If the vote passes, the Secretary merges the PR. If it fails, the PR is closed and kept on record.

## The annual meeting

- Held on the **second Thursday of April**, during Open Hack Night (6 pm).
- Agenda:
  1. Treasurer's report;
  2. election results;
  3. bylaw changes;
  4. open floor.
- The new board appoints Zone Bosses and Leads by 30 April.

## Records

- This repository holds the only official text of the bylaws and policies. The website builds its pages directly from it.
- Every adopted change is a merged PR, and the git history is the full change record.
- Board minutes are added to `minutes/` by PR. Closed-session matters are only summarized.
- Members may inspect CGW's records as Missouri law provides.
