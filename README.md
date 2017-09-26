# mat2ft
convert eeg data matrix to fieldtrip data structure

    mat2ft transform a matrix into fieldtrip data structure 
    ft_data = mat2ft(X, fs) transforms the data in X (samples x channels x
    trials) into a fieldtrip compatible data structure
    
    ft_data = mat2ft(X, fs, varargin)
        accepts optional arguments:
        'labels' - 1xChannels cell array of channels labels
        'offset' - pre-stimulus offset, in seconds
 
    shenin@gc.cuny.edu
    simon.henin@nyumc.org
    (c) September, 25th, 2017
    Sept. 25th 2007 - version 1.0
 
