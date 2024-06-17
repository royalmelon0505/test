# Mixing Left and Right-Hand Driving Data in a Hierarchical Framework with LLM Generation

Here is the Prompt about the Sample Generation with LMM in this paper

The `pre_prompt.md` reveals how to describe the tasks involved before actually input MetaData so that LLM can understand the requirements for generating new MetaData. The generation requirement is `The ego car moves slightly faster than before.`

The `gen_sample.md` gives a demo of the inputs and outputs of the actual generation of a sample.  Besides, the distribution of the generated samples in the future position for the overall dataset and the special dataset is visualized respectively.


`pre_prompt2.md` and `pre_prompt3.md` are other Pre-prompts. The generation requirement of `pre_prompt2.md` is `I hope the other surrounding cars can move faster, and make the ego car move slower.`  The generation requirement of `pre_prompt3.md` is `I hope the ego vehicle can change lane to the left.`
