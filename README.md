# GitSec
This repository consolidates the most relevant information on CVEs from two open sources of security artifacts: the GitHub Advisory Database, which is a comprehensive collection of CVEs and GitHub-originated security advisories affecting the open-source community, and Nomisec, a repository that automatically gathers and stores links to repositories containing proof-of-concept code on GitHub. Both databases are free, open-source resources created for and by the community.

Each folder contains .JSON files with relevant information about CVEs, including the CVE identifier, details, descriptions, topics, severity, references, links to proof-of-concept (PoC) code, CWE IDs, and a temporal description of the same vulnerability present in both repositories.

Note: Since each vulnerability (CVE) in the Nomisec repository may have multiple artifacts linked within GitHub, an identifier is added to the name of each .JSON file that contains more than one artifact in Nomisec. For example, if a file named 'CVE-2011-2523-19.JSON' has '-19' appended before the '.JSON' extension, it indicates that there are 19 Nomisec references associated with that particular file.
