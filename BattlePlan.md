# Tudat battle plan

## Introduction

This document connects Tudat team members to topics of activity. It is both a list of activities and it designates people to coordinate those activities. It is not a mandate (forcing people to take action), it is a map (connecting people to activities). If you are assigned to an activity that you do not want to be part of, remove yourself from it (but let others know the activity needs attention). 

This is a living document in all senses, in regards to activities and the associated people. 

## Objectives

We intend to use this document as an overview of the effort our team members dedicate to all aspects of Tudat. It is a management tool, to allocate people to project activities, as well as a central point for new (or forgetful) team members to get the general idea of the on-going activities and points of contact for those activities.

## Nomenclature

### Activity areas

To better communicate between ourselves, we'll define the term activity areas to be the top-most level of grouping different types of activities. Each area should be orthogonal to any other area, i.e., there is no overlap in terms of action, although there may be conceptual overlaps, e.g., funding may dictate feature development.

Ideally, each [activity area](#Activity-areas) would map directly to one of the [Kanban boards](https://github.com/orgs/tudat-team/projects). This is, however, not necessary (see [Activities](#Activities), below).

### Activities

Under each [activity area](#Activity-areas), there are *Activities*; for example if an [activity area](#Activity-areas) is *Development*, an activity could be *Refactoring*. These are a collection of tasks that aim at a specific purpose that generally falls within the [activity area](#Activity-areas). 
Any of these names are up for grabs. If you have a better name, just edit this document. The main purpose is to be clear and easy to communicate between ourselves.
Populate Activities with a description, status and resources that allow a new contributor to easily pick up this activity.

Instead of linking an [Activity Area](#Activity-areas) to a Kanban board (see above), it may make more sense for a Kanban board to relate to a specific Activity. This makes particularly sense when an Activity requires numerous tasks, which would otherwise overwhelm the Kanban board associated with the [Activity Area](#Activity-areas).

### Tasks

Under each activity, there are *tasks*. These are usually very technical in their nature, specific to each activity and outside the scope of this document. We use the [Kanban boards](https://github.com/orgs/tudat-team/projects) to keep track of tasks.

## Conflicts

This document does not intend to duplicate with the Kanban boards. Those are activity-specific tasks and are used to coordinate their progress. In slack, these boards are also called "Task trackers", see [this post by Fillippo](https://tudat.slack.com/archives/C0202QZAQFK/p1620420704058700). Coordination of [Activities](#Activities) is highly encouraged to take place in the project boards. Here, we're making an inventory of those [Activities](#Activities) from a higher level, without going into much detail as to technical implementations or planning.

## Roles

### Coordinators

We intend to have one *Coordinator* per [activity area](#Activity-areas). This person is the administrator, point of contact, and/or any other role that sits in a position with a vantage point to aggregate knowledge of what was, is, and will be taking place within a certain [activity area](#Activity-areas). The Coordinator should not, in general, make unilateral decisions, but should instead coordinate an appropriate level of consensus among the necessary stakeholders.
The roles tend to be assigned to people who, for one reason or another, are most likely to remain associated with Tudat over a (sufficiently) long period of time. Below, the Coordinators' names follow the [activity area](#Activity-areas) titles to make their role as prominent as possible.

### Activity leaders

We intend to assign people to coordinate each activity. These are people who are coordinating the (technical) work and maintain the overview and knowledge of the progress of all tasks within each activity. They tend to be (heavily) involved in doing the work (i.e. the tasks within an activity), but this is not mandatory; you can have an activity leader who is only coordinating the tasks. It would be most favourable if each Tudat team member is assigned a very limited number of current [Activities](#Activities), at most 2, so that they can focus their attention more effectively. Below, the activity leaders' names follow the activity titles to make their role as prominent as possible.

### Aditional comments

Although, it is necessary to have [activity areas](#Activity-areas) with [Coordinators](#Coordinators) (otherwise there is a collection of [Activities](#Activities) that lack coordination), it is not necessary to have a leader for each activity. There can be [Activities](#Activities) that are dormant, for whatever reason, but are important enough to be part of Tudat's roster of desirable [Activities](#Activities). In the future, these could be used as an evolving roadmap

## Workflow

Anyone can edit this document, but the [Coordinator](#Coordinators) of the Project Management [activity area](#Activity-areas) is ultimately responsible for keeping it up to date. By design, there are not many details that need to be maintained; those are (relevant to both [activity areas](#Activity-areas) or [Activities](#Activities)):
1. Addition or suppression 
2. Updating the description and resource list
3. Updating the status (relevant only to [Activities](#Activities))

Additionally, [Coordinators](#Coordinators) should also keep their [activity area](#Activity-areas) updated in this document, but this does not preclude the [Coordinator](#Coordinators) of the Project Management [activity area](#Activity-areas) from his/her responsibility to this role.

Keep the [Coordinators](#Coordinators)/[Activity leaders](#Activity-leaders) in the title of the [Activity areas](#Activity-areas)/[Activities](#Activities); in this way, it is possible to get an overview of the assigned people from the ToC (once that is working).

## Activity areas

### Documentation - Kevin Cowan

**Description:** (unnecessary)
**Resources:**
* [#documentation channel](https://tudat.slack.com/archives/C01NSEK6CLC)
* [tudat-space.readthedocs.io](https://tudat-space.readthedocs.io/en/latest/) ([tudat-space](https://github.com/tudat-team/tudat-space) repository)
* [tudat-blog.readthedocs.io](https://tudat-blog.readthedocs.io/en/latest/) ([tudat-team/blog](https://github.com/tudat-team/blog) repository)
* [tudatpy-examples](https://github.com/tudat-team/tudatpy-examples) repository
* [tudatpy-tutorials-binder](https://github.com/tudat-team/tudatpy-tutorials-binder) repository

#### User documentation - Jonas Hener, Filippo Oggionni

**Description:** API and algorithm documentation, user oriented, attractive, easy to read, largely immutable, describes how to use existing facilities in Tudat, autocompletion in PyCharm.
**Status:** TBD
**Resources:** (please add more if relevant):
* [tudat-multidoc](https://github.com/tudat-team/tudat-multidoc) repository
* [[TASK TRACKER]](https://tudat.slack.com/archives/C0202QZAQFK/p1620420704058700)
* [https://tudat.slack.com/archives/C01NSEK6CLC/p1616945620018500](https://tudat.slack.com/archives/C01NSEK6CLC/p1616945620018500)
* [https://tudat.slack.com/archives/C01NSEK6CLC/p1620655705006500](https://tudat.slack.com/archives/C01NSEK6CLC/p1620655705006500)
* [User Documentation Board](https://github.com/orgs/tudat-team/projects/9)

#### Developer documentation - Filippo Oggionni, Geoffrey Garrett (Dominic Dirkx)

**Description:** Guides, tips and tricks, development resources, useful links, describes how to develop new features in Tudat and records how existing ones are set up, how to expose C++ code to python.
**Status:** TBD
**Resources:** (please add more if relevant):
* [tudat-developer.readthedocs.io](https://github.com/orgs/tudat-team/projects/9)
* [Developer documentation project board](https://github.com/orgs/tudat-team/projects/6)
* [tudat-developer-docs repository](https://github.com/tudat-team/tudat-developer-docs)
* [developer-primer repository](https://github.com/tudat-team/developer-primer)

#### Code browser - João Encarnação

**Description:** doxygen-generated interactive code, possibly to be added to the developer documentation
**Status:** To be initiated
**Resources:**
* TBD

### Development - Dominic Dirkx

**Description:** (unnecessary)
**Resources:**
* [tudat](https://github.com/tudat-team/tudat) repository

### Maintenance and refactoring, Estimation code - Dominic Dirkx

**Description:** a significant rewrite of the interfaces of the estimation framework in Tudat.
**Status:** observation model creation and observation simulation input close to finished. Observation output data and metadata handling not yet started.
**Resources:**
* [Estimation Refactoring project board](https://github.com/orgs/tudat-team/projects/7)
* [https://github.com/tudat-team/tudat/tree/feature/esimation_refactor](https://github.com/tudat-team/tudat/tree/feature/esimation_refactor)

#### Maintenance and refactoring, MGA-DSM - Dominic Dirkx

**Description:** Refactoring of interplanetary trajectory design, to allow for more flexible and module code use. 
**Status:** Initial version of code is finished, Python interfaces are not quite up to date with latest C++ version, documentation not yet present.
**Resources:**
* [https://github.com/tudat-team/tudat/tree/feature/mga_dsm_refactor_new](https://github.com/tudat-team/tudat/tree/feature/mga_dsm_refactor_new)

#### Maintenance and refactoring, Low-thrust - Dominic Dirkx

**Description:** refactoring of low-thrust trajectory design code, to be consistent with the MGA-DSM framework above. Will allow for combination of low- and high-thrust legs with (un)powered flybys
**Status:** Holographic shaping and spherical shaping code largely refactored to allow for compatibility with new framework
**Resources:**
* [https://github.com/tudat-team/tudat/tree/feature/low_thrust_leg_refactor](https://github.com/tudat-team/tudat/tree/feature/low_thrust_leg_refactor)

#### Testing

**Description:** set up and development of tools to certify Tudat runs as expected in the supported OSs
**Resources:**
* TBD

### Ecosystem - Geoffrey Garret

**Description:** development of the connection between python and the C++ code and all the voodoo behind conda packaging, user-removed build procedure, or anything related to increasing the ease of use, access, reach, and universality of Tudat.
**Resources:**
* [#installation channel](https://tudat.slack.com/archives/CUJMUDBEU)
* [tudat-bundle](https://github.com/tudat-team/tudat-bundle) repository
* [tudat-feedstock](https://github.com/tudat-team/tudat-feedstock) repository
* [tudatpy-feedstock](https://github.com/tudat-team/tudatpy-feedstock) repository
* [tudat-resources-feedstock](https://github.com/tudat-team/tudat-resources-feedstock) repository
* [tudat-resources](https://github.com/tudat-team/tudat-resources) repository
* [cspice-cmake-feedstock](https://github.com/tudat-team/cspice-cmake-feedstock) repository
* [cspice-cmake](https://github.com/tudat-team/cspice-cmake) repository
* [sofa-cmake-feedstock](https://github.com/tudat-team/sofa-cmake-feedstock) repository
* [sofa-cmake](https://github.com/tudat-team/sofa-cmake) repository
* [nrlmsise-00-feedstock](https://github.com/tudat-team/nrlmsise-00-feedstock) repository
* [nrlmsise-00-cmake](https://github.com/tudat-team/nrlmsise-00-cmake) repository
* [tudat-team/status](https://github.com/tudat-team/status) repository
* [test-feedstock](https://github.com/tudat-team/test-feedstock) repository

#### Exposing C++ to TudatPy - TBD
**Description:** ensuring all features present in the C++ code are available in the python interface
**Resources:**
* TBD

### Project management - João Encarnação

**Description:** (unnecessary)
**Resources:**
* [project-management](https://github.com/tudat-team/project-management) repository
* [Project Management](https://github.com/orgs/tudat-team/projects/8) Kanban board

#### Strategy and funding - João Encarnação


#### Activity: Strategy and funding - João Encarnação

**Description:** Long-term planning, development directions, what features to not develop, securing people and funding to reach the planned objectives
**Resources:**
* TBD

#### Outreach - TBD
**Description:** Efforts to make Tudat known to the student, researcher, programming community, and scientific community
**Resources:**
* [https://tudat.slack.com/archives/C0202QZAQFK/p1619090877001800](https://tudat.slack.com/archives/C0202QZAQFK/p1619090877001800)
