# Deepsort
A recurrent neural network based sorting algorithm.

## How it works?
RNNs can compute any arbitrary function, given finite resources since they are "Turing Complete" machines. I have used a sequence to sequence (seq2seq) based neural network model. I have chosen this model since, both the input and output are sequences. Input being unsorted sequence of integers and the output being the sorted sequence of integers. 

I achieved 99.5% accuracy after 50,000 epochs. 

## Results
For the purpose of evaluating the performance (in terms of correct predictions) of this algorithm, I have considered that the input sequence will be of length = 15 and that the maximum number in this sequence will be <= 100. The success rate is evaluated as (number of correct predictions)/(number of trials). 

| Number of Trials | Success Rate | 
| ------------     | ------------ |
| 100              | 97%          |
| 1000             | 96%          |
| 10000            | 95%          |

## Screenshots 
Below is an example of sorting using deepsort -
![alt text](https://github.com/mayank26saxena/deepsort/blob/master/images/epochs-and-accuracy-.png)

## To Do
- [ ] Convert into a Python package. 
- [ ] Try with different sequence lengths and max number. 
- [ ] Add plots. 

## Contributions 
All patches are welcome!

## License
MIT License - see the [LICENSE](https://github.com/mayank26saxena/deepsort/blob/master/LICENSE) file for details.

## Credits
1) [https://github.com/keras-team/keras/blob/master/examples/addition_rnn.py](https://github.com/keras-team/keras/blob/master/examples/addition_rnn.py)
2) [http://shashank-gupta.com/2016/07/22/learning-to-sort-using-seq2seq/](http://shashank-gupta.com/2016/07/22/learning-to-sort-using-seq2seq/)
