# GenAIJudge

We present a Proof of Concept (PoC) for a tool with the following capabilities. Our approach involves using ChaptGPT to intelligently: 
1. Summarize the problem and solution
2. ⁠Comment and provide rating for different rubrics 
3. ⁠Summarize the proposal 
4. ⁠(Future) Highlight key sentences in proposals

The approach highlights the proof of concept using 50 samples to successfully demonstrate that this tool is capable of reducing the workload of judges.


**AIEarthHack.ipynb**: Jupyter notebook to preprocess the dataset. Identify key startegies used in the project and score them on the individual categories to further rank the proposals. The metrics/key features selected for evaluation are dynamic and can be modified.

**Harvard Hack Proposals Visualization.ipynb**: Jupyter notebook to visualize proposals embedded using Sentence Transformer. After cleaning, the summaries are embedded and visualized in 3D. Human judges can interactively select the proposals of interest and disregard clusters of uninteresting proposals.

**dataset.csv**: Cleaned dataset of summaries.

<img width="960" alt="Screenshot 2024-01-07 203501" src="https://github.com/johri-lab/GenAIJudge/assets/26346395/24bbeee6-b18f-4982-8840-5470810b3197">

