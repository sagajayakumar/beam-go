# beam-go

## Steps to Run word count for the sample text using GO language

- [Download and install Go lang here](https://go.dev/)
- Post installation initialize go modules using following command
    - go mod init example/hello
- RUn the below command to get the SDK from github repo
    - go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
- Run below command to install word count from the github repo
    - go install github.com/apache/beam/sdks/v2/go/examples/wordcount 
- Below command executes the wordcount with sample input provided and writes the output to a file
    - wordcount --input sample.txt --output counts
