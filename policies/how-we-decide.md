# How we decide

*Proposed policy. The board adopts it to take effect with the bylaws. Not yet adopted.*

CGW makes decisions in two separate ways:

| | **Member votes** | **Board votes** |
|---|---|---|
| Decides | Who sits on the board; what the bylaws say; dissolution or merger | Everything else: all policy, the budget, appointments, discipline |
| Who votes | Every full member in good standing (not hardship or legacy members) | The four directors |
| When | Voting opens at the annual meeting (second Thursday of April, in place of Open Hack Night) and runs 8 days, or a special vote | Any time |
| How | Secret ballot by email link, through Dolibarr. It records who voted and the totals, never how anyone voted | Reviews on a GitHub pull request, or a vote at a board meeting |
| Passes with | Quorum, then a majority (two-thirds for bylaw changes) | 3 of the 4 directors |

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

A typo or formatting fix that doesn't change meaning is labeled `editorial`, and the Secretary may merge it without a vote. For the bylaws, the Secretary lists each such correction in the next member-vote notice (bylaws 5.8).

## Board votes: on GitHub

Policy changes are decided on the PR itself (bylaws 5.10).

1. **Comment period.** Members have 7 days after the Discord announcement to comment before the vote closes.
2. **Directors review the PR.** Approve means yes; "Request changes" means no. A director with a conflict of interest doesn't review.
3. **Passing.** Once 3 directors approve and the comment period is over, the Secretary merges the PR. The policy takes effect when merged, unless the PR names a later date.
4. **Confirming.** The PR and its reviews are the record. If every director in office approved, the change is final. Otherwise the board confirms it at its next meeting. If the board doesn't confirm it, the Secretary reverts it the same day.
5. **Urgent changes.** For safety or legal urgency, the board may skip the comment period if every director in office approves.

GitHub enforces this: `main` is protected, a change reaches it only through a PR with 3 approving reviews from the directors team, and approvals are dismissed when new commits are pushed, so every yes is on the final text.

Other board decisions, such as spending, appointments, and discipline, are made at board meetings and recorded in the minutes.

## Board meetings

- The board meets at least quarterly. Each regular meeting is posted on Discord at least 7 days ahead, with the agenda.
- Members may attend (bylaws 3.4).

## Member votes: by ballot

Bylaw changes and elections are not decided on GitHub. GitHub only holds the text being voted on.

Members vote on two things: bylaw changes and the board. The board sets policy, the waiver, and the member agreement itself, and appoints Zone Bosses.

Dolibarr runs the vote. The Secretary works it from buttons in emails, without logging in; the President gets the same emails and can press them if the Secretary can't.

1. **Getting on the ballot.** The board puts a bylaw PR to a member vote (bylaws 5.1).
2. **Notice.** At least 14 days before the annual meeting, the Secretary presses **Send notice**. Every full member who will have been a member for 30 days by the meeting gets it by email (bylaws 5.3, 5.4), with the proposed text and a **Run for a board seat** button. The Secretary posts it on Discord.
3. **Running for a seat.** A member presses the button in the notice, picks one seat, and may add a short statement for the ballot. Dolibarr checks they can run: a full member in good standing, 18 or older, and not running for another seat. Members can also be nominated at the meeting if they are there and agree. Nominations close when voting opens.
4. **Discussion.** The week before the meeting, members discuss the proposals on the PR and on Discord. The Secretary presses **Send reminder** to email the candidates so far and a link to the discussion.
5. **At the meeting** members discuss and change the proposed text. The Secretary updates the PR, then presses **Open voting**: Dolibarr tags the final commit `ballot/<yyyy-mm-dd>`, takes the voter roll (full members in good standing, members for at least 30 days), and emails each one a personal ballot link. Nobody who joins later gets a ballot. The roll is confidential, because it shows who holds a hardship waiver.
6. **Ballot.** Yes, No, or Abstain on each bylaw question; for each seat, pick a candidate or abstain (a seat with one candidate is Yes, No, or Abstain). Voting stays open for 8 days. A member who lost their link enters their email and the last 2 digits of their member ID at columbiagadgetworks.org/voting, and the link is sent again to the address on file. Two days before voting closes, the Secretary can press **Remind non-voters**.
7. **Counting.** When voting closes, Dolibarr counts the ballots, checks quorum and the share needed, emails the result to the Secretary and the President, and posts it on the PR: eligible voters, ballots cast, whether quorum was met, the totals, and the outcome. A tie for a seat goes to the President as an email with a button for each tied candidate (bylaws 5.7).
8. **Adoption.** If the vote passes, the Secretary merges the PR. If it fails, the PR is closed and kept on record.

## The annual meeting

- Held on the **second Thursday of April**, 6 to 8 pm, at 1404 Grand Ave, Unit B, Columbia, in place of Open Hack Night: there is no Open Hack Night that evening. The first is on Thursday 8 April 2027.
- Agenda:
  1. Treasurer's report;
  2. the proposed bylaw changes: discussion and final changes;
  3. candidates: nominations from the floor, and each candidate may speak;
  4. the Secretary opens voting.
- Results go out when voting closes, 8 days later.
- The new board appoints Zone Bosses and Leads by 30 April. Until then, everyone already in a role stays in it.

### What is on the ballot

| Question | Passes with |
|---|---|
| Each proposed bylaw change, as tagged `ballot/<yyyy-mm-dd>` when voting opens: Yes, No, or Abstain. At the first annual meeting, a single question: do you ratify the bylaws? | Two-thirds of votes cast (bylaws 5.6) |
| The President, Vice President, Secretary, and Treasurer, one race per seat: pick a candidate or abstain. A seat with one candidate is Yes, No, or Abstain | Most votes, ties broken by the President (bylaws 5.7); a lone candidate needs a majority of votes cast |

- **Who votes:** full members (Standard or Supporter dues) in good standing who joined at least 30 days before the annual meeting (bylaws 5.4). Hardship and Legacy members don't vote (bylaws 2.1). Only voters get the notice and the ballot.
- **When:** voting opens during the meeting, after the discussion, and stays open for 8 days, until about 7 pm on the Friday of the following week. The ballot email gives the exact time.
- **Quorum:** ballots from at least 10% of the full members on the voter roll, and no fewer than 5. Abstentions count toward quorum but not as votes cast (bylaws 5.6).
- **First annual meeting:** the election counts only if the bylaws are ratified. If they are not, the current officers stay in office and the board brings revised bylaws to the members within 120 days (bylaws 5.9).

### Calendar and reminders

Dolibarr emails the Secretary and the President a button for each voting step when it is due: send notice, send reminder, open voting, remind non-voters. The rest runs from the calendar:

- **CGW's calendar** has the annual meeting as a yearly event, second Thursday of April, 6 to 8 pm, with `Promote: yes` in its description. That Thursday's Open Hack Night is deleted from the calendar each year.
- **Discord.** The website copies calendar events to the Discord server's Events list about five weeks ahead.
- **Social posts and email.** The Content Studio announces the meeting two weeks ahead and reminds two days ahead, on Discord `#shop-news` and the other channels. It also includes the meeting in the April "Coming up at CGW" email.
- **Board reminders.** Yearly tasks in Dolibarr's deadline reminders nag the people responsible for the steps below that have no button.

### Steps before the vote

"The meeting" is the annual meeting, the second Thursday of April.

| By | Step | Who |
|---|---|---|
| 15 January | On CGW's Google Calendar, check the annual meeting is there as a yearly event (second Thursday of April, 6 to 8 pm, with `Promote: yes` in the description), and delete that night's Open Hack Night. The website, Discord, the Studio's posts, and the April email then follow automatically. Check the yearly tasks in Dolibarr's deadline reminders | Secretary |
| January board meeting | Run a test vote in Dolibarr with the directors | Board |
| February board meeting | Approve the proposed bylaw changes for the ballot | Board |
| 30 days before the meeting | Last day to join and still vote (bylaws 5.4) | |
| 14 days before the meeting | Press **Send notice** in the Dolibarr email: every voter gets the proposed text and a **Run for a board seat** button. Post the notice on Discord. Nominations open | Secretary |
| 7 days before the meeting | Discussion week. Press **Send reminder**: the candidates so far and a link to the discussion | Secretary |
| The meeting, 6 pm | Treasurer's report; discussion and final changes to the bylaws; nominations from the floor, and candidates speak. The Secretary updates the pull request and presses **Open voting** before the meeting ends. Nominations close | President, Secretary |
| 6 days after the meeting | Press **Remind non-voters** | Secretary |
| 8 days after the meeting, about 7 pm | Voting closes. Dolibarr counts the ballots, emails the result to the Secretary and the President, and posts it on the ballot pull request | Automatic |

### Steps after the vote

| By | Step | Who |
|---|---|---|
| When voting closes | If a bylaw change passed, merge its pull request; if it failed, close it | Secretary |
| 30 April | The new board appoints Zone Bosses and Leads | Board |
| May | Yearly conflict-of-interest statements (`conflict-of-interest.md`) | Secretary |
| 31 May | Budget for the fiscal year starting 1 June | Treasurer, board |

### First annual meeting only (2027)

| By | Step | Who |
|---|---|---|
| Thu 28 Jan 2027 | Turn on branch protection for `main`; report what Coterie said about coverage for 16–17-year-old members and D&O insurance; merge the website's policies pages (ColumbiaGadgetWorks/website pull request 26) and point the site's waiver and member agreement pages at them | Board |
| Mon 1 Feb 2027 | Ask every current member to accept the new member agreement in Dolibarr (it covers notices and ballots by email) | Secretary |
| Thu 25 Feb 2027, 8 pm | Special board meeting: approve the proposed bylaw text, adopt the bylaws subject to ratification (bylaws 5.9), and adopt the policies, waiver, and member agreement to take effect with the bylaws | Board |
| When voting closes | If the bylaws are ratified, set `status: adopted` in `site.yaml` and remove the "Proposed" lines from each page | Secretary |
| The Monday after | Close the Legacy rate: Legacy members move to Standard or leave. Load the new agreement and waiver into Dolibarr | Treasurer |

## Records

- This repository holds the only official text of the bylaws and policies. The website builds its pages directly from it.
- Every adopted change is a merged PR, and the git history is the full change record.
- Board minutes are added to `minutes/` by PR. Closed-session matters are only summarized.
- Members may inspect CGW's records as Missouri law provides.
