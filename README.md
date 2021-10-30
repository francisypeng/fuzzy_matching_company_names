# fuzzy_matching_company_names
Data cleaning and fuzzy matching company names.

Francis Peng <br>
BA Economics/Mathematics, Music - May 2023 <br>
Emory University Department of Economics

The following notebook desscribes and executes the process of cleaning a large dataset of NYSE stock listings as well as matching company names from two different datasets. In this process, the rapidfuzz library is used to implement fuzzy matching. Fuzzy matching is needed as the same company may appear differently in the two datasets. For example, the same company might be listed as "X Corporation" in one dataset and "X Corp" in the other. These are the same comapny, and thus should be matched as such.

This fuzzy matching process was developed for the purposes of the following working papers:

    Fohlin, Caroline (2020) “Crisis and Innovation:  The Transformation of the New York Stock Exchange from the Great War to the Great Depression,” working paper, Emory University.

    Fohlin, Caroline and Phoebe Lei (2020) “The Determinants of the Volume of Initial Public Offerings During the Great Depression and World War II,” working paper, Emory University


To protect the integrity of these unpublished materials, the source datasets are not output in their entirety anywhere in the following notebook. Only the final result table has been displayed to show that the process does indeed work.
