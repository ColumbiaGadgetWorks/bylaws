# Bylaws v4 review: suggestions and open questions

*Review of `main` at 0a1b4e4 (bylaws draft v4 and all policies), 12 October 2026. Working notes only: this file is not in `site.yaml`, and it should be deleted before anything is merged to `main`.*

*This is an AI review, not legal advice. Statute references are from memory of RSMo chapter 355 and the Model Nonprofit Corporation Act it follows; the lawyer should confirm them.*

How to use this: Part A lists problems I'd fix whatever you decide. Part B lists the questions only you can answer; write your answer under each one and I'll turn the answers into edits.

---

## Part A. Suggested fixes

### A1. Inconsistencies and gaps in the text (should fix)

1. **Annual meeting agenda is out of order.** `how-we-decide.md` puts "election results" and "bylaw changes" on the agenda, but bylaws 5.6 says the ballot closes *at the end of* the meeting, so there are no results to announce. Fix: close the ballot at a set time (say 7:15 pm), count during the Treasurer's report and open floor, and announce results last.
2. **Nominations deadline doesn't match the calendar.** Policy says nominations close 7 days before voting opens, which is Wed 24 Mar 2027; the calendar says Tue 23 Mar. Pick one. (The other calendar dates check out: notice on 1 Mar is 30 days before the ballot opens, within 10–60, and the ballot is open more than 7 days.)
3. **"The Secretary records the votes" conflicts with a secret ballot** (5.6). Say the Secretary records *who voted* and *the totals*, never how anyone voted.
4. **The Secretary runs an election they're probably a candidate in.** In April every seat is up, so every director, including whoever counts and whoever checks the count, may be on the ballot. Fix: the board appoints one or two non-candidate members as tellers for each election; they and the Secretary certify the result.
5. **"Editorial" merges can touch the bylaws.** `how-we-decide.md` lets the Secretary merge typo fixes "to the bylaws or a policy" without a vote, but bylaws 5.1 says only members amend the bylaws. Either limit editorial merges to policy files, or add one line to the bylaws allowing non-substantive corrections (typos, cross-references, renumbering) with the change reported at the next member vote.
6. **The grace period makes people lose their vote early.** Bylaws 2.1–2.2 say good standing requires *current* dues; `membership.md` says membership lasts 30 days after a missed payment. So for those 30 days someone is a member but not in good standing, and can't vote if the roll is pulled that day. Say a member stays in good standing until their membership ends.
7. **"Majority" is defined three ways.** 5.10 says "majority vote", 5.11 "a majority of directors", 5.12 "majority of directors present". Say plainly: a policy change needs 3 directors (a majority of the *fixed number*, five), at a meeting or on GitHub.
8. **Board quorum can shrink to one person.** 5.12 sets quorum as a majority of directors *in office*. With four vacancies, one director is a quorum. Suggest: quorum is 3 directors; if fewer than 3 are in office, the remaining directors may only fill vacancies or call a member vote (this pairs with 3.5).
9. **Expulsion can become impossible after recusals.** 2.4 needs two-thirds of *directors in office* (4 of 5), but `conflict-and-discipline.md` says an involved director doesn't vote. If two directors are involved, only 3 can vote and the 4 needed can't be reached. Use "two-thirds of the directors eligible to vote, and at least 3".
10. **What happens if quorum fails** at the annual vote isn't stated. Add: the current directors hold over, and the board reruns the vote within 60 days.
11. **Election mechanics are missing:** a seat with only one candidate (elected without a contest, or still on the ballot?), a seat with no candidate (vacancy, filled under 3.5), someone nominated for two seats (3.2 allows only one; must they choose before the ballot is printed?), and write-ins (allowed or not).
12. **Abstentions.** 5.7 counts them toward quorum; 5.8 says "votes cast". State that abstentions are not votes cast, so they don't count against a two-thirds threshold.
13. **A director who stops being a member.** Say a seat becomes vacant if the director's membership ends, for example after 30 days of unpaid dues.
14. **Removed directors can be reappointed.** If members remove a director (3.6), the board could appoint the same person to the vacancy (3.5). Bar that until the next annual meeting.
15. **The removal-for-absence rule (3.6) almost never applies.** With quarterly meetings, three missed meetings in a row is nine months of a twelve-month term. Suggest "two regular meetings in a row, or half of them in twelve months".
16. **Board-confirmation outcome is undefined (5.12).** If the board, at its meeting, declines to confirm a merged policy change, what happens? Say it is reverted by the Secretary the same day.
17. **"All five directors" in the urgent-change rule** (`how-we-decide.md`) can't be met while a seat is vacant. Use "every director in office".
18. **Role terms leave a gap.** Zone Boss and Lead terms "end 30 April", and the new board appoints "by 30 April". If it's late, every zone is unrun. Say roles continue until reappointed or replaced.
19. **Policy effective date wording differs:** bylaws 5.10 "when it is published", policy "when merged". Pick "when merged" (publishing depends on the website build hook).
20. **The waiver is wrong for 16–17-year-olds.** Section 8 has the signer state "I am at least 18 years old", but 16–17-year-old members are told to sign it. Add a separate parent or guardian section, and have the lawyer check it: Missouri courts have not clearly enforced a parent's advance release of a child's negligence claims, so the waiver may protect CGW much less for minors than for adults.

### A2. Structure suggestions (recommended)

21. **Move tool names out of the bylaws.** "Discord" (5.4) and "GitHub" and "pull request" (5.11) are in the bylaws, so switching chat platforms or git hosts would need a two-thirds member vote. Write "the member chat channel and the governance repository named in policy" and keep the names in `how-we-decide.md`.
22. **Protect the electorate from a board policy change.** Membership requirements live in policy (2.1), so the board could change who is eligible (dues, hardship rules) right before a contested election or removal vote. Add: a policy change affecting who may vote does not apply to a member vote whose notice has already gone out.
23. **Write the transition into the bylaws.** The April 2027 ballot elects a Shop Steward under bylaws being adopted on that same ballot. Add a transition clause: "The election held with the adoption vote is conducted under these bylaws and takes effect only if they are adopted. If they are not adopted, the [2019] bylaws govern and the board holds over until a new election within 90 days." Also put the adoption vote on the ballot *first*.
24. **Petition timing.** 5.3 makes the board "call" a vote within 45 days but doesn't say when it must happen. Suggest notice within 30 days of the petition and voting within 90; if the board misses the deadline, the petitioners may send notice themselves (that is the Missouri default).
25. **Signing authority.** The bylaws never say who signs contracts for CGW. Add: the President or Treasurer, or another director the board authorizes, subject to the two-signature rule in `money.md`.
26. **Indemnification.** Add two lines: CGW may advance defense costs, and the board may buy insurance for directors, officers, and volunteers (D&O). Ask Coterie whether you already have D&O coverage; general liability usually doesn't include it.
27. **Committees.** If the board ever delegates *board* power (not volunteer roles) to a committee, Missouri requires the committee to have at least two directors. One sentence in section 6 covers it.
28. **Public-benefit wording.** In 1.1, say "a Missouri public benefit corporation with members". That is the chapter 355 category a 501(c)(3) falls into, and it decides which statute defaults apply.
29. **IRS-friendly policies.** If CGW ever files Form 990 or 990-EZ instead of the 990-N, the form asks about a written conflict-of-interest policy with annual disclosure, a whistleblower policy, and a document-retention policy. Bylaws 3.8 is a start; a one-page `policies/conflict-of-interest.md` based on the IRS sample, with an annual disclosure form for directors and Zone Bosses, would cover it. The Teacher Fund matters here: a director who teaches gets paid, so they should not vote on Teacher Fund rates.
30. **Supporter receipts.** A $100 payment that buys $50 of membership is a "quid pro quo contribution" over $75, so the IRS requires a written statement of the deductible amount. Have Dolibarr's receipt say so.
31. **ID photos.** The signup collects a photo of each member's ID. Say in policy how long it is kept and who can see it, for example deleted 30 days after membership ends.
32. **Tie Legacy dues to a date, not to adoption.** Right now Legacy members vote on bylaws whose adoption raises their own dues by $10, which looks odd and ties a policy to the bylaws vote. Use a date, such as 1 June 2027, the start of the fiscal year.
33. **Lock down the repository** so the rules match what GitHub enforces: branch protection on `main` requiring 3 approving reviews from a `@directors` team (CODEOWNERS), with stale approvals dismissed when new commits are pushed, so a director's yes is always on the final text.
34. **"Limit someone's access for a set time"** (`conflict-and-discipline.md`) has no ceiling, so a long ban could become a suspension without the 2.4 notice and hearing. Set a maximum, for example 30 days; anything longer goes through 2.4.
35. **Complaints about a director**, or about the whole board, have no path. Suggest: they go to any two uninvolved directors; if fewer than two are uninvolved, an outside mediator.

---

## Part B. Open questions for you

Carried over from the session summary (now B1–B10), plus new ones. Where I lean one way, I say so.

### Legal and records

**B1. The 2019 bylaws.** Have you found them? If not, who will look (old Google Drive, Discord around February 2019, founders), and by when? They decide whether the adoption vote itself follows the right amendment process.
> Answer:

**B2. Lawyer.** Is a Missouri attorney available, and can one review cover all of these: the waiver (including minors, A20), GitHub voting by 3 of 5 without a meeting, the petition threshold, and email notice? A single bundled review costs less than separate ones.
> Answer:

**B3. Insurance.** Has anyone asked Coterie about 16–17-year-old members and under-16 visitors, and whether CGW has D&O coverage (A26)?
> Answer:

### Members and voting

**B4. Petition threshold** to force a member vote: 10% (at least 2), or the Missouri default of 5%? *Lean: 5%, at least 3.* It is the statutory default, so it is legally safe, and with a small membership the difference is one or two people.
> Answer:

**B5. How many members** does CGW have now, and how many do you expect by April? With fewer than 50, the "at least 5" floor is the real quorum, and that floor is low for a bylaws rewrite. Do you want a higher floor (8 or 10)?
> Answer:

**B6. Should 16–17-year-old members vote?** As written they're full members with a vote (but can't run). Keep that, or make voting 18+?
> Answer:

**B7. Ballot method:** Helios, a paid service (ElectionBuddy or OpaVote), paper at the meeting, or a custom tool later? *Lean: online only (Helios or ElectionBuddy), with a laptop at the meeting for anyone who hasn't voted.* Mixing paper and online means checking every paper voter against the online roll to stop double votes.
> Answer:

**B8. Email consent:** add "I agree to receive official CGW notices and ballots by email" to the member agreement? *Lean: yes.* Also: what do you do for a member with no email, postal mail?
> Answer:

**B9. Tellers (A4):** OK for the board to appoint non-candidate members to run and count each election?
> Answer:

### Board

**B10. Fifth seat:** Shop Steward or Membership Director?
> Answer:

**B11. Staggered terms?** All five seats turn over every April, so a single election could replace everyone. Stagger (for example President, Secretary, and Shop Steward in odd years, the others in even years, two-year terms), or keep one-year terms for everyone?
> Answer:

**B12. Term limits?** None now. Leave it that way, or set something like no more than 4 consecutive years in the same seat?
> Answer:

**B13. GitHub accounts.** Will every director have, and actually use, a GitHub account? If one won't, how do they vote on policy PRs (the Secretary records an emailed vote on the PR)?
> Answer:

**B14. Board meeting notice to members.** Meetings are open to members, but nothing requires telling members when they are. Post the schedule on Discord at least 7 days ahead?
> Answer:

### Money and membership

**B15. Hardship cap:** 20% of members (or 4, whichever is more), or case by case?
> Answer:

**B16. Two-director sign-off threshold:** $250, $500, or $1,000?
> Answer:

**B17. Supporter tier:** is Supporter offered only monthly, or also quarterly like Standard?
> Answer:

**B18. Zone Boss duties:** is "at least one class a quarter" realistic for every zone, or should it be "at least two a year"? A rule most Zone Bosses miss weakens the others.
> Answer:

**B19. "Keep politics and religion out of the shop"** (conduct policy): keep it as is, or narrow it to "don't campaign or proselytize"? The broad version is hard to enforce evenly and sits awkwardly next to the nondiscrimination clause that protects religion.
> Answer:

### Rollout

**B20. When do the policies take effect?** The README says nothing is adopted until April, but policies are board decisions. The current board could adopt them now under the 2019 bylaws, then hold the advisory endorsement in April. Or wait for April?
> Answer:

**B21. Repository name:** keep `bylaws`, or rename to `policies`?
> Answer:

**B22. Website rebuilds:** set the `WEBSITE_BUILD_HOOK` secret now?
> Answer:

**B23. Website PR:** merge now with the "Draft" banner, or wait for final text? *Lean: merge now.* Members can't comment on what they can't find, and the banner makes the status clear.
> Answer:

**B24. Who drafts what next?** Should I turn Part A into pull requests now (one for the bylaws, one per policy), or wait for your Part B answers first?
> Answer:
