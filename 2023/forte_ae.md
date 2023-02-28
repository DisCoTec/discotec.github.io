[![](discotec2023-banner.v2.jpeg)](https://www.discotec.org/2023/)

# Artefact Evaluation
[FORTE 2023](https://www.discotec.org/2023/forte) this year includes an artefact evaluation performed by the artefact evaluation committee (AEC). The goal of the artefact evaluation is to enable future researchers to more effectively build on and compare with previous work. The Artefact Evaluation Committee (AEC) will review the artefact. We will be attributing 3 badges, according to [EAPLS guidelines](https://eapls.org/pages/artifact_badges/):
1.	Artefact **functional**: documented, consistent, complete, exercisable;
2.	Artefact **reusable**: exceeding functional, by being carefully documented and well-structured for reuse and repurposing, see below for details;
3.	Artefact **available**: available on a publicly accessible archival repository to a permanent repository that provides a Digital Object Identifier (DOI).

Authors of **regular papers** are invited (but not required) to submit a relevant artefact for evaluation by the artefact evaluation committee (AEC). Authors of **tool papers** are required to submit an artefact to the AEC and this artefact should satisfy at least the requirements for the **functional badge**. Acceptance of tool papers is conditional on successful artefact evaluation.

Members of the artefact evaluation committee and the program committee are asked to use submitted artefacts for the sole purpose of evaluating the contribution associated with the artefact.

## Important Dates
* Saturday March 11, 2023: authors submit artefact
* March 30-31, 2023: rebuttal period
* Friday April 7, 2023: author notification

## Submission Guidelines
Submission site: [https://easychair.org/conferences/?conf=forte2023](https://easychair.org/conferences/?conf=forte2023). Please select the “FORTE AEC 2023” track when making a new submission and use the same title (and pdf of the paper) as for the FORTE submission.

A final artefact submission should consist of
* an **abstract**
    * that summarises the artefact and explains its relation to the paper including
    * a URL from which a **.zip** file containing the artefact can be downloaded – we encourage you to provide a DOI – and
    * the **SHA256** checksum of the .zip file (on submission), and,
    * if applicable, a description of any special requirements beyond a VM or Docker image (e.g., cloud-computing resources, certain hardware, etc.), and,
    * if you are aiming for a reusable badge, an explanation why you believe your artefact is reusable, and
* a **.pdf** file of the submitted paper.

When uploading your artefact to the URL, please update the **SHA256** checksum of the .zip file in the abstract. You can generate the checksum using the following command-line tools.
* Linux: sha256sum <file>
* Windows: CertUtil -hashfile <file> SHA256
* MacOS: shasum -a 256 <file>
    
## Packaging Guidelines
Your artefact .zip file must contain the following elements.
* The **artefact**, i.e., data, software, libraries, scripts, etc. required to replicate the results of your paper. Please prepare a Docker Image or a Virtual Machine. You could use VirtualBox to save a VM image as an OVA file.
* A **LICENSE** file. This does not need to be complicated. Your licence simply needs to allow the artefact evaluation chairs to download and distribute the artefact to the artefact evaluation committee members and the artefact evaluation committee members must be allowed to evaluate the artefact, e.g., use, execute, and modify the artefact for the purpose of artefact evaluation.
* A **README** text file that introduces the artefact to the user and guides the user through replication of your results. Ideally, it should consist of the following parts:
    * Any additional requirements for running the artefact, such as hardware requirements or additional proprietary software;
    * The expected total runtime to run the experiments;
    * Detailed and specific reproducibility instructions to setup and use the artefact to replicate the results in the paper; including an explanation which claims and results cannot be replicated and why.
    
If you are not in a position to prepare the artefact as above, please contact PC chairs for an alternative arrangement. For instance, if you cannot provide us with a VM that contains licensed software, e.g., MatLab, please contact us, so we can find a solution.

## Evaluation Criteria
All artefacts are evaluated by the artefact evaluation committee. Each artefact will be reviewed by at least two committee members, ideally three. Reviewers will read the paper and explore the artefact to evaluate how well the artefact supports the claims and results of the paper.
    
### Criteria for the “functional” badge
The evaluation and the awarding of the **functional** badge is based on the following questions:
* Is the artefact **documented**, i.e., at minimum, an inventory of artefacts is included, and sufficient description to enable the artefacts to be exercised is included.
* Is the artefact **consistent**, i.e., relevant to the associated paper, significantly contributing to the generation of its main results?
* Is the artefact **complete**, i.e., and as far as possible, are all components relevant to the associated paper included?
* Is the artefact **runnable**, i.e., can the software/scripts that generates the results in the associated paper be executed successfully, and can included data be accessed and appropriately manipulated?
    
### Criteria for the “available” badge
To get the **available** badge, please upload your VM to a permanent repository that provides a DOI, such as Zenodo, figshare, or Dryad and use this DOI link in your artefact submission.
    
### Additional criteria for the “reusable” badge
Artefacts seeking the “reusable” badge need to clear a significantly higher bar than functional artefacts. First, they must be available, i.e., receive an “available” badge. Second, we expect a higher level of quality during the evaluation of the functional level. Third, in addition to the criteria from the functional level, they are evaluated against the following criteria: 
* Does the artefact have a licence which allows reuse, repurposing, and which is easy to use?
* Are all dependencies and used libraries well documented and up to date?
* Does the artefact README explain in sufficient detail how the artefact can be used beyond the paper?
* Does the artefact provide documented interfaces for extensions, or is the artefact open source?
* Can the artefact be used in a different environment, e.g., built on another system, used outside of the VM or Docker image, etc.?
    
## Contact
For any questions please contact the two AE chairs:
* Tom van Dijk (t.vandijk@utwente.nl)
* Mário Pereira (mjp.pereira@fct.unl.pt)
