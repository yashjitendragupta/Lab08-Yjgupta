Github Repo: github.com/yashjitendragupta/Lab08-Yjgupta/
Teammates: Yash Gupta, N/A
______________________________________________________________________

question 1: 
NUMBER_DIC = {
    697 : {
        1209 : 1,
        1336 : 2,
        1477 : 3,
    },
    770 : {
        1209 : 4,
        1336 : 5,
        1477 : 6,
    },
    852 : {
        1209 : 7,
        1336 : 8,
        1477 : 9,
    },
    941 : 0,
}
5055034455

question 2:

get_peak_freqs() splits the frequency array into the two analytical bands, then proceeds to record the index of the highest point in each band. To do this, it parses each band using get_max_freq. Lastly, get_number_from_frq() uses the number dictionary and matches the low freq and high freq to their closest values in the dict.