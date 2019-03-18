# Python for Machine Learning

## Intro

- Python을 계속 사용하면서 Data를 다루는 데에 있어 기초가 부족하다는 것을 느꼈기 때문에 Machine Learning과 관련된 Python Code들을 정리하고자 한다.
- Numpy, Pandas, Matplotlib 등 Data Handling에 보다 더 집중하여 공부할 것이다.

## Contents

### 01. [Pythonic Code](https://github.com/dongminleeai/Python-for-ML/tree/master/01.%20Pythonic%20Code)

1. [Lecture](https://github.com/dongminleeai/Python-for-ML/tree/master/01.%20Pythonic%20Code/Lecture)

    - [Pythonic Code](https://github.com/dongminleeai/Python-for-ML/blob/master/01.%20Pythonic%20Code/Lecture/01-1.%20Pythonic%20Code.ipynb)
        - Overview
        - Split & Join
        - List Comprehension
        - Enumerate & Zip
        - Lambda & MapReduce
        - Asterisk
        - Data Structure - Collections
        - Linear algebra codes

    - [News Categorization](https://github.com/dongminleeai/Python-for-ML/blob/master/01.%20Pythonic%20Code/Lecture/01-2.%20News%20Categorization.ipynb)
        - One-hot Encoding
        - Bag of words
        - Distance measure
            - Euclidian distance
            - Cosine distance
        - Corpus 만들기 + 단어별 index 생성하기
        - 문서별로 Bag of words vector 생성
        - Cosine similarity로 비교하기
        - Top n similarity news 뽑아내기
        - Accuracy 측정하기

2. [Assignment](https://github.com/dongminleeai/Python-for-ML/tree/master/01.%20Pythonic%20Code/Assignment/1.%20Pythonic%20Code%20Lab)

    - [Pythonic Code Lab](https://github.com/dongminleeai/Python-for-ML/tree/master/01.%20Pythonic%20Code/Assignment/1.%20Pythonic%20Code%20Lab)

        - vector_size_check
        - vector_addition
        - vector_subtraction
        - scalar_vector_product
        - matrix_size_check
        - is_matrix_equal
        - matrix_addition
        - matrix_subtraction
        - matrix_transpose
        - scalar_matrix_product
        - is_product_availability_matrix
        - matrix_product

<br>

### 02. [Data Handling](https://github.com/dongminleeai/Python-for-ML/tree/master/02.%20Data%20Handling)

1. [Lecture](https://github.com/dongminleeai/Python-for-ML/tree/master/02.%20Data%20Handling/Lecture)

    - [Overview](https://github.com/dongminleeai/Python-for-ML/blob/master/02.%20Data%20Handling/Lecture/02-1.%20Overview.ipynb)

    - [Numpy](https://github.com/dongminleeai/Python-for-ML/blob/master/02.%20Data%20Handling/Lecture/02-2.%20Numpy.ipynb)
        - Numpy이란?
        - Numpy 특징
        - Array creation
            - shape
            - dtype
        - Handling shape
            - reshape
            - flatten
        - Indexing & Sclicing
        - Creation function
            - arange
            - ones, zeros & empty
            - something_like
            - identity
            - eye
            - diag
            - random sampling
        - Operation functions
            - sum
            - axis
            - mean & std
            - Mathematical functions
            - concatenate
        - Array operations
            - Operations b/t arrays
            - Element-wise operations
            - Dot product
            - transpose
            - broadcasting
            - Numpy performance
        - Comparisons
            - All & Any
            - Comparison operation
            - np.where
            - argmax & argmin
        - Boolean & Fancy index
            - boolean index
            - fancy index
        - Numpy data i/o
            - loadtxt & savetxt
            - numpy object - npy

    - [Pandas](https://github.com/dongminleeai/Python-for-ML/blob/master/02.%20Data%20Handling/Lecture/02-3.%20Pandas.ipynb)

    - [Matplotlib]()

    - [Data Cleaning]()

2. [Assignment](https://github.com/dongminleeai/Python-for-ML/tree/master/02.%20Data%20Handling/Assignment)

    - [Numpy Lab](https://github.com/dongminleeai/Python-for-ML/tree/master/02.%20Data%20Handling/Assignment/1.%20Numpy%20Lab)

        - n_size_ndarray_creation
        - zero_or_one_or_empty_ndarray
        - change_shape_of_ndarray
        - concat_ndarray
        - normalize_ndarray
        - save_ndarray
        - boolean_index
        - find_nearest_value
        - get_n_largest_values