# Kanban board use guidelines

## TL;DR

* This document describes the guidelines for using the Kanban boards
* Kanban boards provide an overview of the major activities going on at Tudat; they assist the developers choose what to focus on (cf. [this](https://www.youtube.com/watch?v=rIaz-l1Kf8w) and [this](https://www.youtube.com/watch?v=9AexBnRvwv4) youtube video)
* Kanban boards can be found under each [Project](https://github.com/orgs/tudat-team/projects); it is preferred that we use the "Projects" tab under [tudat-team](https://github.com/orgs/tudat-team) and not a specific repository (e.g. [tudat-space](https://github.com/tudat-team/tudat-space/projects)) because in the former we can connect any issue in any repository to any Kanban board
* Each [Project](https://github.com/orgs/tudat-team/projects) (and Kanban Board) should relate to one [Activity Area](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas); if there is the need for one additional Kanban Board, we should add an additional [Activity Area](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas) to the [Battle Plan](https://github.com/tudat-team/project-management/blob/main/BattlePlan)
* [Activities](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities) may relate to one specific Kanban card if that activity is small enough; ultimately, it is up to the [Activity Leader](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Leaders) to determine how their activity is best represented in the Kanban boards, i.e. with zero, one or multiple cards
* Each Kanban card should be linked to a GitHub Issue, so that it is easy to refer to the discussion related to that board; each issue should be assigned to a team member (who may not necessarily be the [Activity Leader](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Leaders))
* Not all GitHub Issues should be linked to a Kanban board; only those issues relevant enough to a particular [Activity](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities)

## Introduction

This document provides guidelines for the consistent use of the Kanban board. This [Agile Development](https://www.agilealliance.org/agile101/) tool was selected because it is readily available in GitHub and provides [many benefits](https://getnave.com/blog/kanban-benefits/).

Kanban boards can be found under each [Project](https://github.com/orgs/tudat-team/projects). It is better to use the "Projects" tab under [tudat-team](https://github.com/orgs/tudat-team) to create a Kanban board. Alternatively, it is also possible to do it in a specific repository (e.g. [tudat-space](https://github.com/tudat-team/tudat-space/projects)). The problem with the latter is that it is restricted to issues related to this repository. The former circumvents this restriction and any issue in any repository can be connected to any Kanban board (as long as that repository is in [tudat-team](https://github.com/orgs/tudat-team)).

Feel free to propose modifications to these guidelines by opening a GitHub issue. 

## Objectives
  
In addition to the numerous advantages of Kanban boards in the context of Agile Development, the Tudat team, in particular the [Coordinators](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Coordinators), need to be able to get an overview of the progress of the [Activities](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities) in their [Activity Area](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas). This is problematic without any tool because the efforts of the Tudat team are spread over a wide range of topics.

## Workflow and relation with the [Battle Plan](https://github.com/tudat-team/project-management/blob/main/BattlePlan)

An [Activity Area](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas) should be associated with one [Project](https://github.com/orgs/tudat-team/projects). There is no strict requirement for this to be the case, but it generally makes sense to keep the same hierarchy levels across the whole set of tools used in Tudat (the same [should be the case in Slack](https://github.com/tudat-team/project-management/issues/9)). 

It is up to the [Coordinator](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Coordinators) of an [Activity Area](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas)/Kanban board to monitor and manage the progress of the corresponding activities, namely setting up Kanban columns. For example if they are labelled:

* To Do
* In progress
* Done

or

* Backing
* Up Next
* In Progress
* On Hold
* Done

or any other setup. The [Coordinator](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Coordinators) also defines the maximum number of cards in each Column (if he/she so desires), which has to be done informally because it does not seem to be implemented in GitHub.

When a new [Activity](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities) is identified, it should be added to the [Battle Plan](https://github.com/tudat-team/project-management/blob/main/BattlePlan) and a Kanban card (or more) created in the corresponding Kanban board. From here onwards, it is up to the corresponding [Activity Leader](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Leaders) to move the card through the columns. In principle, there is no need for the [Activity Leader](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Leaders) to notify the [Coordinator](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Coordinators) of changes in the Kanban board, it is up to the latter to maintain an eye on the progress of this [Activity Area](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas).

## GitHub Issues

It is recommended we connect a GitHub issue to the Kanban board card. Generally, once that issue is closed, the card should be moved to the last column of the Kanban board.

The issues that are relevant to connect to cards describe the progress of an [Activity](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities). They should not relate to a bug in the code or any other technical issue that does not transpire to the [Activity's](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities) progress. These should not be connected with the Kanban boards (as they are now envisioned; later on we may have an [Activity Area](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas) which focuses on fixing bugs).

## Duplication of work

It may seem that there is somewhat double work in maintaining both the Kanban boards and the [Battle Plan](https://github.com/tudat-team/project-management/blob/main/BattlePlan). However, the two tools focus on different objectives:

* the Kanban boards are used by [Coordinators](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Coordinators) and [Activity Leaders](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Leaders) to manage their efforts and progress;
* the [Battle Plan](https://github.com/tudat-team/project-management/blob/main/BattlePlan) is an onboarding document that also aggregates all [Activity Areas](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas), [Activities](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities) and respective resources.

In other words, someone joining the Tudat team (and is committed to management activities) would get acquainted with what is going on through the [Battle Plan](https://github.com/tudat-team/project-management/blob/main/BattlePlan). This document not only shows an overview of Tudat, but also of the team members, their respective responsibilities and which online resources are relevant. They would then be assigned an [Activity](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities) (or [Activity Area](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas)) and focus on the respective card (or Kanban board).

Some [Activity Areas](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activity-Areas) may be less prone to [Activities](https://github.com/tudat-team/project-management/blob/main/BattlePlan.md#Activities) that regularly go through the life cycle of starting, progressing, being reviewed and ending. In case of Project Management, for example, there are *types of activities*. The respective [Kanban board](https://github.com/orgs/tudat-team/projects/8) is populated with activities that are posted whenever they are identified, with no immediate relation to the aforementioned *types of activities*.