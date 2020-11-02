* We introduce a new technology called progressive layer dropping (PLD) to speed the training of Transformer-based networks through efficient and robust compressed training. PLD takes training dynamics and stability of Transformer networks into accounts and sparsely update Transformer blocks following a progressive dropping schedule, which smoothly increases the layer dropping rate for each mini-batch as training evolves along both the temporal and the model depth dimension. PLD is able to allow the pre-training to be **2.5X faster** to get similar accuracy on downstream tasks. This feature enables fast training, not at the cost of excessive hardware  resources. 

  * For detailed technology deep dive, see our [technical report](XXX).
  * For more information on how to use PLD, see our [Progressive layer dropping tutorial](https://www.deepspeed.ai/tutorials/progressive_layer_dropping/).
  * The source code for PLD can be found in the [DeepSpeed repo](https://github.com/microsoft/deepspeed).