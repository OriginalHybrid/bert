# bert

This notebook has 2 parts:

**Part 1** Apply BERT to QA, and illustrate the details.

**Part 2** Download a model that's *already been fine-tuned* for question answering, and try it out on our own text! 

For something like text classification, we definitely want to fine-tune BERT on your own dataset. For question answering, however, it seems like you may be able to get decent results using a model that's already been fine-tuned on the SQuAD benchmark. In this Notebook, we'll do exactly that, and see that it performs well on text that wasn't in the SQuAD dataset.