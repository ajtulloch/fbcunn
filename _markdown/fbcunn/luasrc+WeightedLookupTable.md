

### WeightedLookupTable.lua ###

Copyright 2004-present Facebook. All Rights Reserved.

<a name="fbcunn.WeightedLookupTable.dok"></a>


## fbcunn.WeightedLookupTable ##


<a class="entityLink" href="https://github.com/facebook/fbcunn/blob/fbf20ca05e68c2058907539c806db18c204ba074/luasrc/WeightedLookupTable.lua#L52">[src]</a>
<a name="fbcunn.WeightedLookupTable:updateOutput"></a>


### fbcunn.WeightedLookupTable:updateOutput(input) ###


Parameters:
* `Input` should be an n x 2 tensor where the first column is dictionary indexes
   and the second column is weights.



#### Undocumented methods ####

<a name="fbcunn.WeightedLookupTable"></a>
 * `fbcunn.WeightedLookupTable(nIndex, ...)`
<a name="fbcunn.WeightedLookupTable:reset"></a>
 * `fbcunn.WeightedLookupTable:reset(stdv)`
<a name="fbcunn.WeightedLookupTable:zeroGradParameters"></a>
 * `fbcunn.WeightedLookupTable:zeroGradParameters()`
<a name="fbcunn.WeightedLookupTable:accGradParameters"></a>
 * `fbcunn.WeightedLookupTable:accGradParameters(input, gradOutput, scale)`
<a name="fbcunn.WeightedLookupTable:accUpdateGradParameters"></a>
 * `fbcunn.WeightedLookupTable:accUpdateGradParameters(input, gradOutput, lr)`
<a name="fbcunn.WeightedLookupTable:updateParameters"></a>
 * `fbcunn.WeightedLookupTable:updateParameters(learningRate)`
