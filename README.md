# 📜 GPT Model with Reinforcement Learning for Shakespearean Writing 🎭

This is a GPT model built from scratch that utilizes Reinforcement Learning with Human Feedback (RLHF) to generate positive or negative recreations of Shakespeare's writing style.

## 📚 Dataset
The dataset used for this project is the [`Tiny Shakespeare`](https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt) dataset which contains 40,000 lines of Shakespeare from a variety of his plays. The dataset was preprocessed and tokenized before being used to train the GPT model.

## 🤖 Model
The GPT model used in this project is a basic implementation of the GPT architecture. The model consists of a transformer encoder-decoder architecture with a fixed length context window. The model was trained using the Shakespeare dataset and was fine-tuned using RLHF to generate positive or negative recreations of Shakespeare's writing style.

## 🎓 Reinforcement Learning with Human Feedback
The RLHF algorithm was used to fine-tune the GPT model to generate positive or negative recreations of Shakespeare's writing style. RLHF uses human feedback to provide the model with reward signals for generating text that matches the desired style or does not match the undesired style. The algorithm adjusts the model's parameters accordingly, optimizing the model to generate text that closely resembles Shakespeare's writing style.

## 📊 Results
The GPT model with RLHF was able to generate positive and negative recreations of Shakespeare's writing style with a high degree of accuracy. The model was able to capture the nuances of Shakespeare's language and produce text that closely resembled his writing style. The model was also able to generate new and original text that was consistent with Shakespeare's style.

## 🎉 Conclusion
This project demonstrates the effectiveness of using RLHF to fine-tune GPT models for specific tasks such as recreating the writing style of a particular author. The GPT model with RLHF was able to produce accurate and original text that closely resembled Shakespeare's writing style. The project also demonstrates the power of building models from scratch and the benefits of using open-source tools such as Github to share and collaborate on projects. 💻
