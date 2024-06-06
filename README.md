### Project Description:
Implement an external sort solution to sort a large number of data elements using disk, in ascending order according to their Comparable natural ordering. The process involves loading portions of data into memory, sorting, and saving them as runs, and then merging runs into a single sorted run.

### Topics Covered:
- Buffering
- Writing Runs
- Reading Runs
- Ordering Data Elements from Multiple Iterators
- Basic External Sort Implementation
- Optimization

### Submission Components:
- **InputBuffer:** Complete the iterator() method.
- **RunWriter:** Implement the constructor to write runs.
- **RunReader:** Implement hasNext() and next() methods.
- **OrderedMergeIterator:** Implement the next() method.
- **ExternalSort:** Implement merge(List<String> runNames) method.
- **OptimizedExternalSort:** Implement a more efficient sorting strategy.
  
### Additional Information:
Refer to the detailed document for specific instructions on each part and running unit tests. Ensure compatibility with provided unit tests and consider performance implications of parameters.

### Appendices:
- **Appendix A:** Importing a Java Project
- **Appendix B:** Creating API documents using JavaDoc
