# Urdu Word Embeddings

Vector representations of Urdu words trained over more than 140 million tokens.

## Download

140M tokens, 100K vocabulary, 300-dimensional vectors (110 MB): [urduvec_140M_100K_300d.zip](https://drive.google.com/uc?id=1K_4Fbdv9GJDNjR_avLbzKdJPEMVWdYBm&export=download)

## Usage

Extract the archive and use Python and Gensim to read the embeddings:

~~~~
from gensim.models import word2vec

model = word2vec.Word2Vec.load_word2vec_format('urduvec_140M_100K_300d.bin', binary=True)
~~~~

## Reference

If you find this resource useful in your work then please cite the following paper:

[Urdu Word Embeddings](http://www.lrec-conf.org/proceedings/lrec2018/pdf/148.pdf)

~~~~
@InProceedings{HAIDER18.148,
  author = {Samar Haider},
  title = {Urdu Word Embeddings},
  booktitle = {Proceedings of the Eleventh International Conference on Language Resources and Evaluation (LREC 2018)},
  year = {2018},
  month = {may},
  date = {7-12},
  location = {Miyazaki, Japan},
  editor = {Nicoletta Calzolari (Conference chair) and Khalid Choukri and Christopher Cieri and Thierry Declerck and Sara Goggi and Koiti Hasida and Hitoshi Isahara and Bente Maegaard and Joseph Mariani and Hélène Mazo and Asuncion Moreno and Jan Odijk and Stelios Piperidis and Takenobu Tokunaga},
  publisher = {European Language Resources Association (ELRA)},
  address = {Paris, France},
  isbn = {979-10-95546-00-9},
  language = {english}
  }
~~~~

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
