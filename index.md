# Papers' Recording
## June 2022
### Temporal whitening by power-law adaptation in neocortical neurons
Neural signaling requires a large amount of metabolic energy, so to minimize energy consumption, the neural codes are dynamically modified so as to maximize information transmission, which means a low signal-to-noise ratio. Spike-frequency adaptation's power-law decay at different time scales decorrelates signals temporally distant and correlating temporally close signals. 

A question naturally emerge: how can we describe this adaptation-decay mathematically? There has been some specific hazard functions proposed in mathematical community, such as homogenous step function, and by some probabilistic analysis we can see that homogenous step function may cause heterogeneous temporal correlation. Given a hazard function, can we theoretically analysis its temporal correlation scale? Given a energy-consumption function, can we give an optimal current pattern minimizing energy-consumption?

### Mind the last spike — firing rate models for mesoscopic populations of spiking neurons
Mathematically speaking, synchronization refers to any stability around characteristic solutions: steady states or temporally periodic solutions.

Although there may be the chance that discharging only depends on the last spike, but previous spikes's effect may accumulate to a significant scale, indicating population temporal average as a useful statistic.

## July 2022
### Relations between the statistics of natural images and the response properties of cortical cells
A central problem in neural transmission is that how does the network reduce redundancy? Like Barlow suggests that the purpose of natural image processing is "to represent visual scenes by activity of a sparse selection of reliable and nonredundant (i.e., independent) elements.". This paper talks about how neurons perform temporal/spatial local fourier transform/frequency-selection/Gabor filtering and reduce the order of redundancy in early visual processing.

Notice that n-order redundancy refers to the non-uniformness of the conditional probability given a pair of (n-1)-elements. An interesting example is that, consider a 2-D graph with lines of different orientations from an unknown point, there is a significant second-order redundancy: given two pixels' intensity, we can determine the line's intensity through the two points (second-order conditional probability). The task will be use certain decorrelation to reduce this redundancy and reduce 2-D to 1-D.

Here is how Gabor filtering (locally concentrating, spatial or spatial-temporal, fourier transform) works and reduce redundancy. This is also a strong evidence for decorrelation of neural signals.

### Decorrelation and efficient coding by retinal ganglion cells
Many biologists proposed that neural network uses filtering to reduce redundancy and maximize information transmission. This paper especially discussed spatio-temporal decorrelation, and proposed that the main mechanism to decorrelate is the nonlinearity: antagonistic center and surround regions. By statistical analysis, the authors showed that after convolution of spatio-temporal receptive field and natural stimulus, the correlation are reduced below the correlation in natural stimulus.

