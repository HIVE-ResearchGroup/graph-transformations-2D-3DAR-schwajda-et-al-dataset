# graph-transformations-2D-3DAR-schwajda-et-al-dataset

## Files

- Study1-AllData.xslx (Transformation Methods)
- Study2-AllData.xslx (Groupings)
- Study3-AllData.xslx (Visual Links)

Each containing the collected user study data for time/error rates, as well as SSQ and NASA-TLX in a seperate sheet for each respective study

### Sheets
#### Time+Error
- personID: Anonymous identifier for each participant
- taskNumber: unqiue identifier for each task/trial for a single participant
- requestedCluster: ID of the cluster that was supposed to be selected
- selectionCorrect: whether the participant selected the correct cluster
- searchTime: time in ms from the completion of the transformation until the selection of a cluster
- Condition: tested condition in that trial (used in study 2 onwards)
- transformationMethod: the used transformation method of that trial, either Spawn Constant or UserControlled (used in user study 1)
- Grouping: utilised grouping in this trial (used in study 2)
- visualLink: utilised visual link in that trial (used in study 3)
- TransitionDuration: time in ms it took to complete the transformation
- taskCompletionTime: time in ms it took to complete the transformation and to select a cluster (searchTime + Transitionduration)
- ParticipationS1: user already participated in study 1
- ParticipationS2: ser already participated in study 2
- #studyParticipations: ParticipationS1 + ParticipationS2

#### SSQ
- Person: Anonymous identifier for each participant
- Trial: identifier for each block after the SSQ was filled out: 0 before the start of the study; 1 after the first condition, 2 after the second condition; 3 after the third condition (study 2+3) // last condition (study1); 4 after the last condition (study 2+3)
- Condition: the tested condition of the last block in the study before filling out this SSQ (0 if baseline before actual study start)
- SumScore: accumulated SSQ sore
- NauseaScore: nausea score
- OculomotorScore: oculumotor score
- DisorientationScore: disorientation score
- TotalScore: factorised score

#### NasaTLX
- Person: Anonymous identifier for each participant
- Trial: identifier for each block after the NasaTLX was filled out: 1 after the first condition, 2 after the second condition; 3 after the third condition (study 2+3) // last condition (study1); 4 after the last condition (study 2+3)
- Condition: the tested condition of the last block in the study before filling out this NasaTLX (0 if baseline before actual study start)
- Mental: mental demand
- Temporal: temporal demand
- Performance: overall performance
- Effort: effort
- Frustration: frustration level

