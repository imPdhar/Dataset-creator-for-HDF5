## Raw Dataset converter using h5py

Primary Source: @nsarang

HDF File formats are impressive compressed database/dataset handlers which is built on SQL that is packed in hierarchical binary formats. They are known to be highly efficient in systems using low grade ML algorithms or even with hardware embedded with relatively utilize low performance processors. 

The Dataset is created by implementing integer arrays of images and arranging them hierarchically under their respective classes. 

### Usage:

1.  Input Image dataset directory in Image path specifier.
2. Input h5 dataset directory in dataset_name specifier. 
3. Comment out invalid parameters that seem non-relevant to avoid errors. 
4. Run according to your need for differentiating training and test data. 

## Known errors:

| Issue(s):                                           | Resolution                                       |
| --------------------------------------------------- | ------------------------------------------------ |
| File truncated and path handling error              | Use "\\\\\"  instead of \ while specifying path. |
| x_train, x_validation,x_test not found error        | Comment out folders that are non-existent.       |
| Execution error/ File still running(Jupyter tested) | Shutdown the kernel, reconnect and run.          |

###### Note: If the file running error is thrown even after trying the above method, please exit the notebook, shutdown from the file menu and restart. This is observed on Jupyter Notebook so far and other IDEs are not tested. Feel free to comment after testing. 
