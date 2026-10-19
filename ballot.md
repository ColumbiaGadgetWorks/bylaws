# Ballot: annual meeting, 8 April 2027

*Ballot plan. The board approves the final version at its meeting on Thursday 25 February 2027.*

**Annual meeting:** Thursday 8 April 2027, 6 to 8 pm, at 1404 Grand Ave, Unit B, Columbia. There is no Open Hack Night that evening.

**Voting:** online, from Wednesday 31 March 2027 at 9 am until Thursday 8 April 2027 at 7 pm. Each voter gets a personal ballot link by email. A laptop is set up at the meeting for anyone who hasn't voted yet.

**Who votes:** full members (Standard or Supporter dues) in good standing on Wednesday 31 March 2027. Hardship and Legacy members don't vote (bylaws 2.1).

**Quorum:** ballots from at least 10% of the full members on the voter roll, and no fewer than 5.

## The questions

| # | Question | Kind | Passes with |
|---|---|---|---|
| 1 | Do you ratify the bylaws in [`bylaws.md`](bylaws.md), as tagged `ballot/2027-04-08`? | Binding | Two-thirds of votes cast |
| 2 | Do you endorse the policies in [`policies/`](policies/), the [waiver](signup/waiver.txt), and the [member agreement](signup/membership-agreement.txt)? | Advisory. The board has adopted them to take effect with the bylaws, and will reconsider any that members reject | Majority of votes cast |
| 3 | Elect the President, Vice President, Secretary, Treasurer, and Membership Director | Binding, one race per seat. Counts only if question 1 passes (bylaws 5.11) | Most votes; a lone candidate needs a majority of yes votes |

Abstentions count toward quorum but not as votes cast. If question 1 fails, the current officers stay in office and the board brings revised bylaws to the members within 120 days.

## Steps before the vote

| By | Step | Who |
|---|---|---|
| Thu 28 Jan 2027 | At the quarterly board meeting: confirm the ballot service (Helios Voting unless the board picks another), turn on branch protection for `main`, and report what Coterie said about coverage for 16–17-year-old members and D&O insurance | Board |
| Fri 15 Jan 2027 | On CGW's Google Calendar: add the annual meeting as a yearly event (second Thursday of April, 6 to 8 pm, with `Promote: yes` in the description), and delete the Open Hack Night on 8 April 2027. The website, Discord, the Studio's posts, and the April email then follow automatically | Secretary |
| Fri 15 Jan 2027 | In Dolibarr's deadline reminders, set up the yearly tasks listed in `policies/how-we-decide.md` | Secretary |
| Thu 28 Jan 2027 | Merge the website's policies pages (ColumbiaGadgetWorks/website pull request 26), so columbiagadgetworks.org/policies/ shows this text, and point the site's waiver and member agreement pages at it | Board |
| Thu 25 Feb 2027 | Last day for member comments on pull requests and issues in this repository | Members |
| Thu 25 Feb 2027, 8 pm | **Special board meeting.** The board approves the final text, adopts the bylaws subject to ratification (bylaws 5.11), adopts the policies, waiver, and member agreement to take effect with the bylaws, appoints one or two tellers who aren't candidates, and approves the notice | Board |
| Mon 1 Mar 2027 | Tag the final commit `ballot/2027-04-08`. Send notice by email to members who agreed to email notices, by mail to everyone else, and post it on Discord, with a PDF of the text. Nominations open | Secretary |
| Mon 1 Mar 2027 | Ask every current member to accept the new member agreement in Dolibarr, so notices and ballots can go by email | Membership Director |
| Wed 24 Mar 2027 | Nominations close (7 days before voting opens). Candidate list posted on Discord | Secretary |
| Wed 31 Mar 2027, 9 am | Export the voter roll of full members in good standing from Dolibarr; ballot opens | Secretary and tellers |
| Thu 8 Apr 2027, 6 pm | Annual meeting: Treasurer's report, open floor while the tellers certify the count, then results (bylaws first, then elections). Ballot closes at 7 pm | President, tellers |

## After the vote

| By | Step | Who |
|---|---|---|
| Thu 8 Apr 2027 | Post the result on the ballot pull request and merge it. Set `status: adopted` in `site.yaml` and remove the "Proposed" lines from each page | Secretary |
| Fri 9 Apr 2027 | Close the Legacy rate: Legacy members move to Standard or leave. Load the new agreement and waiver into Dolibarr | Membership Director, Treasurer |
| Fri 30 Apr 2027 | New board appoints Zone Bosses and Leads | Board |
| May 2027 | Yearly conflict-of-interest statements (`policies/conflict-of-interest.md`) | Secretary |
| Mon 31 May 2027 | Budget for the fiscal year starting 1 June | Treasurer, board |
