# Closing the Loop: Testing ChatGPT to Generate Model Explanations to Improve Human Labelling of Sponsored Content on Social Media
*Thales Bertaglia, Stefan Huber, Catalina Goanta, Gerasimos Spanakis, Adriana Iamnitchi*

[Paper link](https://arxiv.org/abs/2306.05115)

## Data
The file `dataset_labels.csv` contains all posts used in the annotation task. Each row includes a post (represented by its shortcode) and each column is the label given by the corresponding annotator. See Section 3.4 of the paper to understand what each subgroup represents. You can access the posts on Instagram through `instagram.com/p/{shortcode}`.

The file `prompt.txt` contains the final version of the ChatGPT prompt used to generate the explanations used to augment the annotation task.

## Citation
```
@misc{bertaglia2023closing,
      title={Closing the Loop: Testing ChatGPT to Generate Model Explanations to Improve Human Labelling of Sponsored Content on Social Media}, 
      author={Thales Bertaglia and Stefan Huber and Catalina Goanta and Gerasimos Spanakis and Adriana Iamnitchi},
      year={2023},
      eprint={2306.05115},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
