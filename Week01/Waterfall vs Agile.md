# Waterfall :vs: Agile Model:

### Waterfall Model:

- The Waterfall Model is a linear sequential flow. 
- As the name suggests, progress flow steadily downwards (like a waterfall) through the phases of software implementation. 
- Any phase in the development process begins only if the previous phase is complete. 
- There is no way to get back to previous phase once its done.
- The usage of the waterfall model can fall under the projects which do not focus on changing the requirements.

<img src="./Images/download.png" style="zoom:120%;" />

#### Stages of Waterfall model

1. **Feasibility Study**: Determines whether the project is financially and technically feasible or not.
2. **Requirements analysis and specification**: All the requirements are understood in this phase and a SRS(Software Requirements Specification) document is also made. All the requirements regarding the software are gathered from the customer to meet their requirements.
3. **Design**: The requirement specifications from first phase are studied in this phase and the system design. The requirements in the SRS are converted into a format that can be coded in a programming language. A Software Design Document is used to document all of this effort (SDD).
4. **Coding and Unit testing**: After the design phase, coding starts and each modules is coded and individually tested referred as unit testing. Each designed module is coded and tested whether it is working properly or not.
5. **Integration and System testing**: All the modules in previous stage which are successfully coded and tested are now integrated together and the whole system is tested to determine whether the complete system is working fine or not after integration.
6. **Maintenance**: Maintenance is the most important phase of a software life cycle. The effort spent on maintenance is 60% of the total effort spent to develop a full software.

|                       Advantages                        |                        Disadvantages                         |
| :-----------------------------------------------------: | :----------------------------------------------------------: |
|                     Simple and Easy                     |                         Rigid model                          |
|                  Base for other models                  |                    No changes/experiments                    |
| Requirements are very well documented, clear and fixed. |                        No parallelism                        |
|         Stages and activities are well defined          | It takes the full lifecycle to deliver a workable solution to the customer |

### Agile Model:

- Latest model and used by many major companies.
- Large projects, move quickly
- Breaking down large project into small chunks(iterations) and then each iteration is passed through stages like develop, test, release and then take feedback, enhance if needed and finally re-release.
- Agile based products don't require any time frame downtime to deploy changes unlike the waterfall model.
- The time to complete an iteration is known as a **Time Box**. Time-box refers to the maximum amount of time needed to deliver an iteration to customers

<img src="./Images/agile.png" style="zoom:120%;" />

#### Agile Manifesto principles:

- **Individuals and interactions** − In Agile development, self-organization and motivation are important, as are interactions like co-location and pair programming.
- **Working software** − Demo working software is considered the best means of communication with the customers to understand their requirements, instead of just depending on documentation.
- **Customer collaboration** − As the requirements cannot be gathered completely in the beginning of the project due to various factors, continuous customer interaction is very important to get proper product requirements.
- **Responding to change** − Agile Development is focused on quick responses to change and continuous development.

|              Advantages               |                        Disadvantages                         |
| :-----------------------------------: | :----------------------------------------------------------: |
| Promotes team work and collaboration  | Depends heavily on customer interaction, so if customer is not clear, team can be driven in the wrong direction |
| Frequent delivery of product/software | Transfer of technology to new team members may be quite challenging due to lack of documentation |
|         Feedback from client          | There is a very high individual dependency, since there is minimum documentation generated |
| Ability to manage changing priorities |        More risk of maintainability and extensibility        |
|          Parallel iterations          |                                                              |
|          Less documentation           |                                                              |
|    Little or no planning required     |                                                              |
|    Gives flexibility to developers    |                                                              |

### Waterfall :vs: Agile Model:

|               Waterfall               |                            Agile                             |
| :-----------------------------------: | :----------------------------------------------------------: |
| Promotes team work and collaboration  | Depends heavily on customer interaction, so if customer is not clear, team can be driven in the wrong direction |
| Frequent delivery of product/software | Transfer of technology to new team members may be quite challenging due to lack of documentation |
|         Feedback from client          | There is a very high individual dependency, since there is minimum documentation generated |
| Ability to manage changing priorities |        More risk of maintainability and extensibility        |
|          Parallel iterations          |                                                              |
|          Less documentation           |                                                              |
|    Little or no planning required     |                                                              |
|    Gives flexibility to developers    |                                                              |



