# Ballot: annual meeting, 8 April 2027

*Ballot plan. The board approves the final version at its meeting on Thursday 25 February 2027.*

**Annual meeting:** Thursday 8 April 2027, 6 to 8 pm, at 1404 Grand Ave, Unit B, Columbia. There is no Open Hack Night that evening.

**Voting:** the Secretary opens voting during the meeting, after the discussion, and it stays open for 8 days, until about 7 pm on Friday 16 April 2027 (the ballot email gives the exact time). Each voter gets a personal ballot link by email.

**Who votes:** full members (Standard or Supporter dues) in good standing who joined on or before Tuesday 9 March 2027, so they have been members for 30 days when voting opens (bylaws 5.5). Hardship and Legacy members don't vote (bylaws 2.1). Only voters get the notice and the ballot.

**Quorum:** ballots from at least 10% of the full members on the voter roll, and no fewer than 5.

## The questions

| # | Question | Kind | Passes with |
|---|---|---|---|
| 1 | Do you ratify the bylaws in [`bylaws.md`](bylaws.md), as tagged `ballot/2027-04-08`? | Binding | Two-thirds of votes cast |
| 2 | Elect the President, Vice President, Secretary, Treasurer, and Membership Director | Binding, one race per seat. Counts only if question 1 passes (bylaws 5.11) | Most votes, ties broken by the President (bylaws 5.9); a lone candidate needs a majority of yes votes |

Abstentions count toward quorum but not as votes cast. If question 1 fails, the current officers stay in office and the board brings revised bylaws to the members within 120 days.

## Steps before the vote

| By | Step | Who |
|---|---|---|
| Fri 15 Jan 2027 | On CGW's Google Calendar: add the annual meeting as a yearly event (second Thursday of April, 6 to 8 pm, with `Promote: yes` in the description), and delete the Open Hack Night on 8 April 2027. The website, Discord, the Studio's posts, and the April email then follow automatically | Secretary |
| Fri 15 Jan 2027 | In Dolibarr's deadline reminders, set up the yearly tasks listed in `policies/how-we-decide.md` | Secretary |
| Thu 28 Jan 2027 | At the quarterly board meeting: run a test vote in Dolibarr with the directors, turn on branch protection for `main`, and report what Coterie said about coverage for 16–17-year-old members and D&O insurance | Board |
| Thu 28 Jan 2027 | Merge the website's policies pages (ColumbiaGadgetWorks/website pull request 26), so columbiagadgetworks.org/policies/ shows this text, and point the site's waiver and member agreement pages at it | Board |
| Mon 1 Feb 2027 | Ask every current member to accept the new member agreement in Dolibarr (it covers notices and ballots by email) | Membership Director |
| Thu 25 Feb 2027, 8 pm | **Special board meeting.** The board approves the proposed bylaw text, adopts the bylaws subject to ratification (bylaws 5.11), and adopts the policies, waiver, and member agreement to take effect with the bylaws | Board |
| Tue 9 Mar 2027 | Last day to join and still vote (30 days before voting opens) | |
| Thu 25 Mar 2027 | Press **Send notice** in the Dolibarr email: every voter gets the proposed text and a **Run for a board seat** button. Post the notice on Discord. Nominations open | Secretary |
| Thu 1 Apr 2027 | Discussion week. Press **Send reminder**: the candidates so far and a link to the discussion | Secretary |
| Thu 8 Apr 2027, 6 pm | **Annual meeting:** Treasurer's report; discussion and final changes to the bylaws; nominations from the floor, and candidates speak. The Secretary updates the pull request and presses **Open voting** before the meeting ends. Nominations close | President, Secretary |
| Wed 14 Apr 2027 | Press **Remind non-voters** | Secretary |
| Fri 16 Apr 2027, about 7 pm | Voting closes. Dolibarr counts the ballots, emails the result to the Secretary and the President, and posts it on the ballot pull request | Automatic |

## After the vote

| By | Step | Who |
|---|---|---|
| Fri 16 Apr 2027 | If the bylaws passed, merge the ballot pull request. Set `status: adopted` in `site.yaml` and remove the "Proposed" lines from each page | Secretary |
| Mon 19 Apr 2027 | Close the Legacy rate: Legacy members move to Standard or leave. Load the new agreement and waiver into Dolibarr | Membership Director, Treasurer |
| Fri 30 Apr 2027 | New board appoints Zone Bosses and Leads | Board |
| May 2027 | Yearly conflict-of-interest statements (`policies/conflict-of-interest.md`) | Secretary |
| Mon 31 May 2027 | Budget for the fiscal year starting 1 June | Treasurer, board |
