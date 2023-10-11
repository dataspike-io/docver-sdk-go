# docver-sdk-go

Document verification go client for API dataspike.io.

Installation:
```sh
go get github.com/dataspike-io/docver-sdk-go
```

## Quick start

```
dc := dataspike.NewDataspikeClient(dataspike.WithSandbox(), dataspike.WithToken("your token"))
applicant, err := dc.GetApplicantByID(applicantID)
```

## Documentation
https://docs.dataspike.io/api