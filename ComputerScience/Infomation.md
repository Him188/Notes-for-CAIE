# Number Representation

##### Why use binary to represent data\[1\]:

- Any electronic device can only read signals in 2 discrete states which are on or off, which is represented by a 1 or 0

# Sound

**Sampling**: <u>amplitude of sound wave taken at different points in time</u>

**Sampling Resolution**: <u>number of bits assigned to each sample</u>

**Sampling Rate**: number of samples taken per unit time

**Bit rate**: number of bits used to store 1 second of sound

**Lossless Compression**: type of compression that allows original data to be perfectly reconstructed from compression

​    **Run-length Encoding**: compression in which sequences with same data value in many consecutive values are stored as a single data value and count

**Lossy Compression**: Data is lost; Decompressed file is not the same as the original

​    **Perceptual coding**: works by reducing certain parts of a sound which are less audible to human hearing

#### Difference between Lossless and Lossy\[3\]:

- Lossless is designed to lost none of the original detail \[1\];
- Lossless technique is based on some form of replacement \[1\]
- Lossy may result in loss of detail compared to original file \[1\]
- (take examples of file formats or compressing techniques) \[1-2\]

# Image

**Pixel**: <u>the smallest picture element which can be drawn</u>

**Image Resolution**: <u>the amount of pixels per centimeter</u>

**Screen Resolution**: <u>the number of pixels which can be viewed horizontally and vertically on the screen</u>

**Color Depth**: <u>number of bits used to represent the color of a single pixel</u>

#### Bitmap\[3\]:

- Made up of pixel;
- Each pixel has one color;
- Color of each pixel stored as a binary number;

#### Benefits of using Vector graphic than bitmap graphic:

- - Benefit: Can resize it without <u>pixilation</u>  
  - Reason: Image is calculated with each <u>adjustment</u>

- - Benefit: Smaller file size  
  - Reason: It stores command, not pixels.

**Multimedia container format**: the wrapper that contains various different types of data.



# Video

**Bit Streaming**: On-demand; Real-time

#### How sound is recorded(sampled) \[3\]:

- Sound wave is sampled <u>as regular interval</u>
- Each sample is stored as a binary number
- Samples are stored in order in a file

**Using a higher sampling resolution** \[2\]:

- Benefit: allows for larger dynamic range\[1\]; more accurate representation\[1\]
- Drawback: bigger files occupies more storage; grater processing power needed\[1\]

#### How it is possible to watch the video without continually pausing\[4\]:

- User needs high bandwidth \[1\];
- Data is streamed into a buffer which stops the video from pausing\[1\]:
- As buffered is empties, it fills up again so that the viewing is continuous\[1\];

#### Progressive Encoding \[2\]:

- Each frame contains the <u>complete image</u>
- All the frame data is recorded at the same time
- The number of images stored is the same as the frame rate

#### Interlaced Encoding\[3\]:

- Single frames are divided into <u>separate fields</u>:
- One field has data for odd numbered rows, another has data for even numbered rows.
- Odd numbered row fields <u>alternate</u> with even numbered row fields
- Viewers see the divided fields <u>simultaneously</u>

#### Differences between <u>Interlaced Encoding</u> and <u>Progressive Encoding</u>:

| Progressive                                      | Interlaced                                       |
| ------------------------------------------------ | ------------------------------------------------ |
| each frame contains the complete image           | each frame contains half of the complete image   |
| frames are not <u>divided into fields</u>        | each frame divided into two fields               |
| complete frames are displayed <u>in sequence</u> | data from two frames is displayed simultaneously |
| has high <u>bandwidth</u> requirements           | halves the transmission bandwidth requirements   |

#### Temporal Redundancy \[2\]:

- Identify the pixels that do not change between frames;
- Records only the differences between frames
