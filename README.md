# ihe-connectathon-gazelle-content

This project is aimed at gathering all the resources which are needed by the Gazelle test bed in the context of the IHE Connectathons: the interoperability model, the test cases, the test data, and any configuration files necessary for the proper functionning of the test bed.

# Project structure

The Project structure is the following:

/{domain}
    - {id}.domain.yaml
    /profiles
        - {id}.profile.yaml
        - ...
    /transactions
        - {id}.transaction.yaml
        - ...
    /value-sets
        - {id}.valueset.json
        - ...
    /interface-templates
        - {transaction}.if-template.yaml
        - ...
    /tests
        - {id}.test.yaml | {id}.mlang
        - ...
    /test-data
        - ??? not yet defined ???
    /validation-profiles
        /{validation-service}
            - [specific configuration files]
        /...
    /simulation-sequences
        /{simulation-service}
            - [specific configuration files]
        /...