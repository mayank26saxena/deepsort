# Deepsort
A recurrent neural network based sorting algorithm.

### How it works?
RNNs can compute any arbitrary function, given finite resources since they are "Turing Complete" machines. I have used a sequence to sequence (seq2seq) based neural network model. Such a model has been chosen, since, in this case, the input and output are both sequences. Input being unsorted sequence of integers and the output being the sorted sequence of the corresponding input. 

### Results
For the purpose of comparing the performance (in terms of running time) of this algorithm, I have considered that the input sequence will be of length = 15 and that the maximum number in this sequence will be <= 100. 

| Algorithm       | Complexity   | Average time | 
| -------------   | ------------ | ------------ |
| Bubble Sort     | O(n^2)       |              |
| Merge Sort      | O(nlog(n))   |              |
| Deep Sort       |              |              |

### To Do
- [ ] Convert into a Python package. 
- [ ] Try with different sequence lengths and max number. 

### Contributions 
All patches are welcome!

### License
MIT License - see the [LICENSE](https://github.com/mayank26saxena/deepsort/blob/master/LICENSE) file for details.

### Credits
1) [https://github.com/keras-team/keras/blob/master/examples/addition_rnn.py](https://github.com/keras-team/keras/blob/master/examples/addition_rnn.py)
2) [http://shashank-gupta.com/2016/07/22/learning-to-sort-using-seq2seq/](http://shashank-gupta.com/2016/07/22/learning-to-sort-using-seq2seq/)
