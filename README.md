# bio-errors
Errors encountered doing bioinformatics

## GATK

|**Error**|**Reason**|**Solution**|**Reference**|
|---|---|---|---|
|terminate called after throwing an instance of 'std::bad_alloc'|not enough memory|allocate more memory|[here](https://gatkforums.broadinstitute.org/gatk/discussion/3071/repeated-bad-alloc-errors-using-the-unifiedgenotyper-tool)|
|s is not a recognized option|short hand option is interpreted as clustering|use full hand option|[here](https://github.com/broadinstitute/barclay/issues/119)|
