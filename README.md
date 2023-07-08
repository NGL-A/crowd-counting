# crowd-counting
Algorithm to count the number of people in a frame

References:
- Overview on crowd counting papers: https://arxiv.org/pdf/2012.15685v2.pdf
- FDST: https://arxiv.org/pdf/1907.07911.pdf

Dataset:
- Fudan-ShangaiTech: https://github.com/sweetyy83/Lstn_fdst_dataset<br /> In *train_data* we removed the duplicated files from:<br />folder 73 → 129(1).json, 130(1).jpg, 130(1).json;<br />folder 91 → 049(1).jpg, 049(1).json, 050(1).jpg, 050(1).json, 051(1).json 
- Mall: https://personal.ie.cuhk.edu.hk/~ccloy/downloads_mall_dataset.html<br /> *Mall dataset* + ground truth
- UCSD: http://www.svcl.ucsd.edu/projects/peoplecnt/<br /> The *Pedestrian Traffic Database* contains more than 30k frames, but only the Groundtruth of the first 2k is available (as .mat file).<br />Hence, we won't use the whole .zip file

