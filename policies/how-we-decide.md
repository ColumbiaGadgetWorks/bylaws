# How we decide

*Policy draft. Not adopted. Covers who decides what, and how changes are proposed, voted on, and recorded.*

## Three layers

| Layer | Where it lives | Who changes it | How |
|---|---|---|---|
| **Bylaws** | `bylaws.md` | Members | Member vote: quorum, then two-thirds of votes cast |
| **Policies** | `policies/` | Board | Board majority, after 7 days for member comment |
| **Zone rules** | The zone's wiki page | The Zone Boss | No vote. Must fit within policy |

If two layers conflict, the higher one wins, in this order: Missouri law, the Articles, the bylaws, policy, zone rules.

**This repository is the only official text.** The website builds its policy pages straight from it. Nobody keeps a separate copy.

## Proposing a change

Any member may propose a change.

1. **Open a pull request** (PR) that edits the file. The diff shows exactly what would change. Without a GitHub account, or if you'd rather not edit, open an issue describing what you want, or ask the Secretary. The Secretary turns it into a PR and credits you.
2. **Announce it.** The Secretary posts the link on Discord.
3. **Discuss it** on the PR. Use GitHub's "suggest changes" to propose wording; the author decides which suggestions to take.

Keep each PR to one topic. A typo or formatting fix that doesn't change meaning is labeled `editorial`, and the Secretary may merge it without a vote.

## Policy changes: the board votes on GitHub

1. **Comment period.** The PR stays open for at least **7 days** after it is announced.
2. **Vote.** Each director votes with a GitHub review:
   - **Approve** = yes;
   - **Request changes** = no;
   - a comment saying "abstain" = abstain.
3. **Passing without a meeting.** If **every** director approves, the PR passes. That counts as unanimous written consent (bylaws 4.5).
4. **Passing at a meeting.** If not every director approves, the PR goes on the agenda for the next board meeting. The Secretary records that vote on the PR and in the minutes.
5. **Adoption.** After the vote passes, the Secretary merges the PR. It takes effect on the merge date unless the PR says otherwise.
6. **Urgent changes.** For safety or legal urgency, the board may skip the comment period by unanimous approval. The PR then takes comments for 7 days after merging, and the board reconsiders at its next meeting if anyone objects.

## Bylaw changes and elections: members vote by secret ballot

1. **Getting on the ballot.** The board puts a bylaw PR to a member vote, or the members require it by petition (bylaws 3.3).
2. **Freezing the text.** The Secretary tags the PR's final commit `ballot/<yyyy-mm-dd>`. Members vote on that exact text. Any later change needs a new notice.
3. **Notice.** The Secretary sends the email notice required by bylaws 3.4. It links to the tagged text and attaches a PDF copy.
4. **Nominations** open with the notice and close 7 days before voting opens. Any eligible member may nominate themselves or another member who agrees.
5. **Ballot.**
   - On the morning voting opens, the Secretary exports the list of members in good standing from Dolibarr. That list is the voter roll.
   - The Secretary loads the roll into the online ballot service. Each member gets a personal voting link by email, and each link works once.
   - Members who don't vote online may vote at the meeting, on a phone or on the shop laptop.
6. **Counting.** When the ballot closes, the Secretary posts on the PR: the number of eligible voters, ballots cast, whether quorum was met, the yes/no/abstain counts, and the result. A second director checks the count.
7. **Adoption.** If the vote passes, the Secretary merges the PR and fills in the adoption date. If it fails, the PR is closed and kept on record.

## The annual meeting

- Held on the **second Thursday of April**, during Open Hack Night (6 pm).
- The ballot opens at least 7 days before and closes at the end of the meeting.
- Agenda:
  1. Treasurer's report;
  2. election results;
  3. bylaw changes;
  4. open floor.
- By 30 April, the new board appoints Zone Bosses and Leads.

## Records

- Every adopted change is a merged PR. The git history is the full change log.
- Board minutes are added to `minutes/` by PR.
- Closed-session matters are only summarized in the minutes.
