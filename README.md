# Tensorflow Experiments

## Style
- Operations that deal with batches may assume that the first dimension of a Tensor is the *batch* dimension.
- An *operation* is a *function* that, given input tensors and parameters, creates a part of the graph and returns output tensors.
- The first arguments should be tensors, followed by parameters, with last argument being the *name* (default: None).
- Tensor arguments should be either a single tensor or an iterable of tensors.
- Non-tensor inputs should be converted to tensors via the *convert_to_tensor* method.
- *op_scope*:
- A *Layer* is an operation that combines variable creation and/or other graph operations.
