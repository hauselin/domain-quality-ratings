# README

You can also visit https://www.domain-quality.info to search for domains.

`domain_ratings.csv` contains ratings generated by our ensemble method (imputation + principal component analysis). For details regarding our methodology, see our [manuscript](https://doi.org/10.1093/pnasnexus/pgad286).

 - `domain`: domain/url
 - `pc1`: first component from PCA (0: lowest quality, 1: highest quality)
 - other columns: see our [manuscript](https://doi.org/10.1093/pnasnexus/pgad286)

If you want only the `pc1` ratings, download `domain_pc1.csv` instead.

# Citation

Lin, H., Lasser, J., Lewandowsky, S., Cole, R., Gully, A., Rand, D. G., & Pennycook, G. (2023). High level of correspondence across different news domain quality rating sets. PNAS Nexus, 2(9), 1-8. https://doi.org/10.1093/pnasnexus/pgad286

```
@article{Lin2023Sep,
	author = {Lin, Hause and Lasser, Jana and Lewandowsky, Stephan and Cole, Rocky and Gully, Andrew and Rand, David G. and Pennycook, Gordon},
	title = {{High level of correspondence across different news domain quality rating sets}},
	journal = {PNAS Nexus},
	volume = {2},
	number = {9},
	pages = {pgad286},
	year = {2023},
	month = sep,
	urldate = {2023-09-14},
	issn = {2752-6542},
	publisher = {Oxford Academic},
	doi = {10.1093/pnasnexus/pgad286},
	URL = {https://doi.org/10.1093/pnasnexus/pgad286},
	eprint = {https://doi.org/10.1093/pnasnexus/pgad286}
	keywords = {misinformation, fact-checking, news quality, journalism standards},
}
```
