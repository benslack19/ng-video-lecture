# Building a GPT from scratch

This is a forked repo of Andrej Karpathy's repo. I'm using it as a vehicle for better understanding transformers. I'm following the YouTube video [Let's build GPT: from scratch, in code, spelled out.](https://www.youtube.com/watch?v=kCc8FmEb1nY).

I'm primarily using `gpt_learning.ipynb` to run code. While Karpathy used Shakespeare, I thought it'd be fun to do something different and so I used Radiohead songs from [MeetShah9](https://raw.githubusercontent.com/MeetShah9/Collection-and-exploration-of-radiohead-lyrics/refs/heads/main/data_collection/radiohead_tracks.csv).

# Setup
Local environment: `torch_env`

*Notes below come from Karpathy's original repo.*

# nanogpt-lecture

Code created in the [Neural Networks: Zero To Hero](https://karpathy.ai/zero-to-hero.html) video lecture series, specifically on the first lecture on nanoGPT. Publishing here as a Github repo so people can easily hack it, walk through the `git log` history of it, etc.

NOTE: sadly I did not go too much into model initialization in the video lecture, but it is quite important for good performance. The current code will train and work fine, but its convergence is slower because it starts off in a not great spot in the weight space. Please see [nanoGPT model.py](https://github.com/karpathy/nanoGPT/blob/master/model.py) for `# init all weights` comment, and especially how it calls the `_init_weights` function. Even more sadly, the code in this repo is a bit different in how it names and stores the various modules, so it's not possible to directly copy paste this code here. My current plan is to publish a supplementary video lecture and cover these parts, then I will also push the exact code changes to this repo. For now I'm keeping it as is so it is almost exactly what we actually covered in the video.

### License

MIT
