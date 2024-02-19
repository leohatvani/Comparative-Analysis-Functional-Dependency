# Comparative Analysis of Text Mining and Clustering Techniques for Assessing Functional Dependency between Manual Test Cases

## Appendix
The supplementary appendix materials for the article
Performance comparison of Different Text Mining and
Clustering Techniques for Functional Dependency are
provided in the upcoming pages.

### Plotting UMAP results
Figures 1 and 2 illustrate the results of utilizing 7 different string distance algorithms for the text mining
where the Agglomerative algorithm is used for the clustering in Figure 1. A total of 5 clusters were achieved
and mirrored by the the Agglomerative clustering algorithm in Figures 1a, 1b, 1c and 1d respectively.
The results of using some normalized compression
distance algorithms for text mining and DBSCAN
and HDBSCAN algorithms are presented in Figures 3
and 4. As emphasized before the HDBSCAN algorithm can provide a cluster of the non-clusterable data
points which can be interpreted as independent test
cases in this study. Generally, the HDBSCAN algorithm provides more clusters compared to all other
utilized clustering algorithms. As we can see in Figures 3a, 3b, 3c, 4a and 4b more than 200 clusters are
generated where each color represent a unique cluster.
However, the combination of the same text mining
method with the DBSCAN leads to having all test
cases inside of one cluster mirrored in Figure 3d. The
visualization results of employing two machine learning approaches are mirrored in Figure 5, where Fig-
ure 5a represents the combination of the Doc2Vec with
Agglomerative and Figure 5b indicates the combination of SBERT with Affinity respectively.

<figure>
    <table>
    <tr>
    <td><figure><img src="figures/Figure1a-Overlap-Agglomerative.png" alt="Overlap coefficient with Agglomerative." title="Overlap coefficient with Agglomerative." >
    <figcaption>(a) Overlap coefficient with Agglomerative.</figcaption></figure></td>
    <td><figure><img src="figures/Figure1b-RatcliffObershelp-Agglomerative.png" alt="Ratcliff-Obershelp with Agglomerative." title="Ratcliff-Obershelp with Agglomerative." >
    <figcaption>(b) Ratcliff-Obershelp with Agglomerative.</figcaption></figure></td>
    </tr>
    <tr>
    <td><figure><img src="figures/Figure1c-Jaro-Agglomerative.png" alt="Jaro with Agglomerative." title="Jaro with Agglomerative." >
    <figcaption>(c) Jaro with Agglomerative.</figcaption></figure></td>
    <td><figure><img src="figures/Figure1d-Levenshtein-Agglomerative.png" alt="Levenshtein with Agglomerative." title="Levenshtein with Agglomerative." >
    <figcaption>(d) Levenshtein with Agglomerative.</figcaption></figure></td>
    </tr>
    </table>
<figcaption> Figure 1 - String distance algorithms are employed for text mining.
</figcaption>
</figure>

<figure>
    <table>
    <tr>
    <td><figure><img src="figures/Figure2a-Jaccard-Affinity.png" alt="Jaccard with Affinity." title="Jaccard with Affinity." >
    <figcaption>(a) Jaccard with Affinity.</figcaption></figure></td>
    <td><figure><img src="figures/Figure2b-SorensenDice-Affinity.png" alt="Sorensen–Dice coefficient with Affinity." title="Sorensen–Dice coefficient with Affinity." >
    <figcaption>(b) Sorensen–Dice coefficient with Affinity.</figcaption></figure></td>
    </tr>
    <tr>
    <td><figure><img src="figures/Figure2c-qgram-DBSCAN.png" alt="$q$-gram with DBSCAN." title="$q$-gram with DBSCAN." >
    <figcaption>(c) $q$-gram with DBSCAN.</figcaption></figure></td>
    </tr>
    </table>
<figcaption> Figure 2 - String distance algorithms are employed for text mining.
</figcaption>
</figure>

<figure>
    <table>
    <tr>
    <td><figure><img src="figures/Figure3a-Bzip2-HDBSCAN.png" alt="bzip with HDBSCAN." title="bzip with HDBSCAN." >
    <figcaption>(a) bzip with HDBSCAN.</figcaption></figure></td>
    <td><figure><img src="figures/Figure3b-Deflate-HDBSCAN.png" alt="Deflate with HDBSCAN." title="Deflate with HDBSCAN." >
    <figcaption>(b) Deflate with HDBSCAN.</figcaption></figure></td>
    </tr>
    <tr>
    <td><figure><img src="figures/Figure3c-Gzip-HDBSCAN.png" alt="gzip with HDBSCAN." title="gzip with HDBSCAN." >
    <figcaption>(c) gzip with HDBSCAN.</figcaption></figure></td>
    <td><figure><img src="figures/Figure3d-Xz-DBSCAN.png" alt="Levenshtein with Agglomerative." title="Levenshtein with Agglomerative." >
    <figcaption>(d) XZ with DBSCAN.</figcaption></figure></td>
    </tr>
    </table>
<figcaption> Figure 3 - Normalized compression distance algorithms are employed for text mining.
</figcaption>
</figure>

<figure>
    <table>
    <tr>
    <td><figure><img src="figures/Figure4a-Zlib-HDBSCAN.png" alt="Zlip with HDBSCAN." title="Zlip with HDBSCAN." >
    <figcaption>(a) Zlip with HDBSCAN.</figcaption></figure></td>
    <td><figure><img src="figures/Figure4b-Zstd-HDBSCAN.png" alt="Zstd with HDBSCAN." title="Zstd with HDBSCAN." >
    <figcaption>(b) Zstd with HDBSCAN.</figcaption></figure></td>
    </tr>
<figcaption> Figure 4 - Normalized compression distance algorithms are employed for text mining.
</figcaption>
</figure>

<figure>
    <table>
    <tr>
    <td><figure><img src="figures/Figure5a-doc2vec-AgglomerativeClustering_UMAP.png" alt="Doc2Vec with Agglomerative." title="Doc2Vec with Agglomerative." >
    <figcaption>(a) Doc2Vec with Agglomerative.</figcaption></figure></td>
    <td><figure><img src="figures/Figure5b-sbert-Affinity.png" alt="SBERT with Affinity." title="SBERT with Affinity." >
    <figcaption>(b) SBERT with Affinity.</figcaption></figure></td>
    </tr>
    </table>
<figcaption> Figure 5 - Machine learning algorithms are employed for text mining.
</figcaption>
</figure>

### The results of sensitivity analysis using the Mantel model

Matrix of Mantel correlations between the employed
text mining algorithms is presented in Figure 6.

<figure>
    <img src="figures/Figure6-Mantel.png" alt="Matrix of Mantel correlations" id="Figure6" title="Matrix of Mantel correlations" >
    <figcaption>Figure 6 - Matrix of Mantel correlations between the employed text mining algorithms (both tokenized and non-
tokenized version) distances between all pairs of 784 source points.The rows and columns of the matrix represent
each of the 28 text mining algorithms. The color of the cell corresponds to the magnitude of the Mantel $r_M$
correlation between the algorithms distances, indicated by the intersection of the row and column.
</figcaption>
</figure>