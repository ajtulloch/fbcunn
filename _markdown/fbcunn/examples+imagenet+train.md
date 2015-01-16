

### train.lua ###

Copyright (c) 2014, Facebook, Inc.
All rights reserved.
This source code is licensed under the BSD-style license found in the
LICENSE file in the root directory of this source tree. An additional grant
of patent rights can be found in the PATENTS file in the same directory.


<a class="entityLink" href="https://github.com/facebook/fbcunn/blob/fbf20ca05e68c2058907539c806db18c204ba074/examples/imagenet/train.lua#L74">[src]</a>
<a name="fbcunn.train"></a>


### fbcunn.train() ###

3. train - this function handles the high-level training loop,
i.e. load data, train model, save model and state to disk

<a class="entityLink" href="https://github.com/facebook/fbcunn/blob/fbf20ca05e68c2058907539c806db18c204ba074/examples/imagenet/train.lua#L149">[src]</a>
<a name="fbcunn.trainBatch"></a>


### fbcunn.trainBatch(dataPointer, labelPointer) ###

4. trainBatch - Used by train() to train a single batch after the data is loaded.
