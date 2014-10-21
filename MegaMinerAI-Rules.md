---
layout: about
title: MegaMinerAI Rules
navbar: megaminerai
---

MegaMinerAI Competition Rules
=============================


Definitions
-----------

The following terms are used in this document:

-   **ACM**: ACM refers to Missouri S&T’s local chapter of the
    Association of Computing Machinery. It is a Recognized Student
    Organization (RSO) at Missouri S&T.

-   **SIG-Game:** Missouri S&T ACM SIG-Game is a special interest group
    of Missouri S&T’s local chapter of ACM. Its purpose is to host
    MegaMinerAI once per semester. This includes logistics involved in
    hosting the competition, as well as development of software
    required to support it.

-   **SIG-Game Developer**: A member of SIG-Game who was exposed to
    game-specific information for MegaMinerAI. SIG-Game maintains a
    list of people who have had access to this information. SIG-Game
    Developers are not eligible for any prizes.

-   **Student Team**: A team comprised entirely of currently enrolled
    students. Each member may be either a full-time or a part-time
    student.

-   **Non-student Team**: A team containing at least one member who is
    **not** enrolled as a full-time student or a part-time student.

Venue
-----

MegaMinerAI is hosted on Missouri S&T’s campus in Rolla, Missouri.
Several rooms in Toomey Hall are reserved for competition. These
reserved rooms are considered the competition venue.

### Traveling Competitors

Competitors who intend to travel to Rolla to participate in MegaMinerAI
should notify SIG-Game as soon as possible. This will enable SIG-Game to
request enough temporary accounts for competitors. Additionally, S&T’s
IT department requires personal contact information from visitors to
enable network access for personal devices. If a visiting competitor
fails to inform SIG-Game of their travel plans, that competitor may be
unable to use S&T’s network to obtain Internet access.

Schedule and Phases of Competition
----------------------------------

All times are local (Central Time)

-   Saturday

    -   12:00 PM - 12:30 PM - **Opening Ceremony**

    -   ~12:30 PM - **Competition begins**

    -   ~6:00 PM - **Quick Draw Tournament**

-   Sunday

    -   12:00 PM - **Competition ends**

    -   ~12:30 PM - **Closing Ceremony**

Registration Fees
-----------------

-   A registration fee of \$24 per team will be collected at the end of
    the Opening Ceremony.

    -   The registration fee is \$24 per team regardless of team size.

-   A team will receive a discount of \$4 for each team member who is a
    dues-paying member of Missouri S&T’s ACM chapter.

    -   For example, a team with exactly two S&T ACM members will
        receive a \$8 discount. Thus, that team’s registration fee
        will be \$16.

    -   Discount eligibility will be determined according to S&T ACM’s
        official roster.

    -   You *must* be a member of ACM at the time of competition to be
        eligible for a discount.

-   Teams who do not pay the registration fee will be removed from the
    competition.

    -   SIG-Game Developers will attempt to contact unpaid teams before
        removing them.

Teams
-----

-   Teams must have at least one member and may not exceed three
    members.

-   Teams must be formed on SIG-Game’s website prior to the start of the
    competition. All code submissions must be made through this site.

-   Prize eligibility varies based on the status of team members. Please
    see the "Eligibility" section below.

Prizes
------

-   Prizes are only awarded to eligible teams (see "Eligibility to win
    prizes").

-   Prizes are awarded to *teams* not to individual members of a team.

    -   It is the responsibility of a prize-winning team to decide how
        prizes should be divided among its members.

-   Prizes from the Final Tournament are awarded in the form of
    Amazon.com Gift Cards as follows:

    -   First place: \$180

    -   Second place: \$120

    -   Third place: \$60

Tournament
----------

### Submitting Code

-   All code submissions must happen through SIG-Game’s website.

-   All code must execute on an Ubuntu 14.04 Linux machine using the
    following restrictions

    -   Makefiles

        -   A GNU Makefile must be at the *top level* of the team’s
            repository

        -   The makefile must able to successfully build the team’s
            program

    -   run.sh file

        -   A Bash script named "run.sh" must be at the *top level* of
            the team’s repository

        -   Executing this script must start the team’s AI program

        -   The script must allow for command line arguments to be
            passed to the compiled executable

-   If a submitted program is not fully built by ``make`` and
    executable with ``run.sh``, the AI may be ineligible for
    participation

    -   For example, a team’s program may compile and run in Eclipse or
        Visual Studio, but if that program does not compile and run as
        described above, that AI will not be run in the final
        tournament

-   Please note that the ShellAI provided to each competitor ***will
    successfully compile and run as described***. Teams should ask
    SIG-Game Developers for help if necessary.

### Quick Draw Tournaments

-   Purpose: An initial tournament on Saturday evening that identifies
    which team is currently in first place. A second Quick Draw
    Tournament may occur at midnight on Sunday

-   Prize: The first-place team will receive their registration fee
    back.

    -   If a team wins more than one Quick Draw Tournament, they will
        only receive their entry fee for the first victory.

-   Tournament Configuration

    -   Triple Elimination

    -   Prize awarded to first place winner

    -   Brackets seeded according to performance in the Arena

Final Tournament
----------------

-   Purpose: The final tournament determines the top three student teams

-   Prize - Outlined in "Prizes" section.

-   Tournament Configuration

    -   Triple Elimination

    -   Prizes awarded to first, second, and third place winners

    -   Brackets seeded according to performance in the Arena

### Global Tournament

-   Purpose: The final tournament determines the top three teams
    (student, non-student, and SIG-Game Developer teams)

-   Prize - No prizes are awarded

-   Tournament Configuration

    -   Triple Elimination

    -   Prizes awarded to first, second, and third place winners

    -   Brackets seeded according to performance in the Arena

Eligibility
-----------

### Eligibility to compete

-   All competitors are expected to be physically present at the
    competition venue.

-   Exceptions for remote competitors may be made at the discretion of
    SIG-Game. Opportunities for remote competition are strictly
    limited to:

    -   SIG-Game Developer Alumni

    -   ACM / MegaMinerAI Sponsors

### Eligibility to win prizes

-   Competitors must participate at the competition venue to remain
    eligible for prizes.

    -   Remote competitors are not eligible to win prizes.

    -   If a prize-winning team is unable to attend the Closing
        Ceremony, they are still eligible to win prizes.

-   All team members *must* be full-time or part-time students to be
    eligible for prizes in the Final Tournament.

    -   If a team has one or more non-student member, that team will be
        ineligible to win prizes in the Final Tournament.

    -   If a team has one or more SIG-Game Developer member, that team
        will be ineligible to win **any** prizes at MegaMinerAI.

Receiving Help
--------------

During the competition, Developers will be available to answer any
questions that competitors may have. If you, as a competitor, have any
questions, please ask them for help. All SIG-Game Developers can be
easily identified, as they will be wearing the T-Shirt for the current
MegaMinerAI.

Cheating and Dishonesty
-----------------------

If a team is suspected of cheating or sabotaging SIG-Game, MegaMinerAI,
or another competing team, SIG-Game will revoke the eligibility of the
saboteur’s entire team and remove that team from the competition. The
final decision to remove a team from competition will be made by the
President of SIG-Game.

Please note that this does not include game strategies. For example, if
an AI is written to perform well against one particular opponent,
SIG-Game does not consider this sabotage. If, however, an AI was
designed to exploit security vulnerabilities in SIG-Game’s
infrastructure or an opponent’s code, SIG-Game would consider this
actionable sabotage.

Other Rules and Policies
------------------------

All other decisions not covered in this document will be made by the
President of SIG-Game or their designee.

Changes to this document
------------------------

-   Changes to this documented will be recorded and made available to
    competitors.

-   Though the history of this document is available, it is the
    responsibility of competitors and other participants to check for
    any and all changes.

Questions and Clarification
---------------------------

If you have questions about MegaMinerAI or need clarifications about its
rules, please email <siggame@mst.edu>.