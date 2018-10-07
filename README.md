# Multi-Resolution CNNs

Report investigating the effect of Multi-Resolution Convolutional Neural Networks on urban sound classification accuracy.

List of notebooks attached:
* Feature Extraction
* Baseline 3-channel
* Baseline 2-channel
* Experiment 1: Multi-Resolution Single-Layer CNN prioritizing Frequency information
* Experiment 2: Multi-Resolution Single-Layer CNN prioritizing Temporal information
* Experiment 3: Multi-Resolution Parallel Pipeline CNN (Short Frequency + Short Time Kernels)
* Experiment 4: Multi-Resolution Parallel Pipeline CNN (Medium Frequency + Medium Time Kernels)
* Experiment 5: Multi-Resolution Parallel Pipeline CNN (Long Frequency + Long Time Kernels)
* Experiment 6: Multi-Resolution Parallel Pipeline CNN (Short & Med Frequency + Short & Med Time Kernels, merged by feature)
* Experiment 7: Multi-Resolution Parallel Pipeline CNN (Short & Med Frequency + Short & Med Time Kernels, merged by size)
* Experiment 8: Multi-Resolution Parallel Pipeline CNN (Med & Long Frequency + Med & Long Time Kernels, merged by feature)
* Experiment 9: Multi-Resolution Parallel Pipeline CNN (Med & Long Frequency + Med & Long Time Kernels, merged by size)
* Experiment 10: Multi-Resolution Parallel Pipeline CNN (Short, Med & Long Freq + Short, Med & Long Time, merged by feature)
* Experiment 11: Multi-Resolution Parallel Pipeline CNN (Short, Med & Long Freq + Short, Med & Long Time, merged by size)
* Experiment 12: Same as 3 but with a second hidden layer before the Softmax output layer
* Experiment 13: Same as 4 but with a second hidden layer before the Softmax output layer
* Experiment 14: Same as 5 but with a second hidden layer before the Softmax output layer
* Experiment 15: Same as 6 but with a second hidden layer before the Softmax output layer
* Experiment 16: Same as 7 but with a second hidden layer before the Softmax output layer
* Experiment 17: Same as 8 but with a second hidden layer before the Softmax output layer
* Experiment 18: Same as 9 but with a second hidden layer before the Softmax output layer
* Experiment 19: Same as 10 but with a second hidden layer before the Softmax output layer
* Experiment 20: Same as 11 but with a second hidden layer before the Softmax output layer
* Experiment 21: Same as 20 but with real-time batch data augmentation.

References: 
Daisuke, N. (2017) UrbanSound Classification. https://github.com/daisukelab/ml-urban-sound
Piczak, K. (2015). Environmental Sound Classification with Convolutional Neural Networks. 
Zhu, X., Kaznady, M. & Hendry, G (2017). Hearing AI: Getting Started with Deep Learning for Audio on Azure. Available at https://blogs.technet.microsoft.com/machinelearning/2018/01/30/hearing-ai-getting-started-with-deep-learning-for-audio-on-azure/
