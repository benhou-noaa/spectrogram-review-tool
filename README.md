# Detection Audio-Visual Review Tool (DART)

## About
Applications of artificial intelligence (AI) technology can greatly improve our ability to rapidly process large acoustic datasets. However, one challenge faced by many programs lies with validating AI classification on novel data. Unlike during the training process, where the truth is known, it is necessary to utilize some method to verify that the scores for new data are accurate. Despite the importance of this task, many extant tools are geared for data analysis rather than reviewing AI output. Further, there is a general need for design guidelines to support the design of this class of software.

## Software
Given this challenge, we developed the detection audio-visual review tool (DART). DART is a graphical tool that allows you to load tabular output generated by an AI process. Given the source audio file, the time of the detection (relative seconds into the given clip), and output class, DART automatically generates a visual representation of the detection comprised of spectrograms of the detection (the specific detection and its context) as well as corresponding audio clips, thereby enabling a human analyst to review and as necessary, make corrections to the classification. Such capabilities support validation efforts and model monitoring capabilities and provide annotation training data that can support future model development. 

## Current Work
At present, we are working on expanding DART's data model to accomodate different tabular formats--this is achieved by having DART parse the specific numeric index of a file rather than hard-coded column names. Further, we are incorporating logic that allows for user-customizable specification of coding buttons so that both the display name and recorded code can be customized. It is our hope that DART can help bioacoustics programs address this challenge and hasten the adoption of AI in bioacoustics. 

## Publications
Please see https://aisel.aisnet.org/amcis2024/sig_hci/sig_hci/13/ to learn more.
