# Ali Omar

I'm a computer science graduate and a Master's student in Data Science for Risk Analysis at Lebanese University. My background is in software development and machine learning. My recent work covers hybrid search and the design of reproducible model comparisons.

## Selected projects

| Project | What I worked on |
| --- | --- |
| [Conditional hybrid retrieval](https://github.com/aliomar139/rag-research) | My coauthors and I extended the Blended RAG approach with a cascade that runs BM25 first. A trained ridge regression model estimates the recall gain from running the two neural retrievers. The gate returns BM25 results when the predicted gain is at or below the threshold. Otherwise, it runs dense MiniLM and learned-sparse SPLADE and combines their rankings with BM25. |
| [Cardiovascular disease label prediction](https://github.com/aliomar139/cardiovascular-disease-prediction) | Compared logistic regression, a decision tree, a random forest, XGBoost, and CatBoost on the same fixed train/test split with group-aware validation. The repository includes the data preparation, training code, and results. |
| [Student burnout, study conditions, and generative AI](https://github.com/aliomar139/student-burnout-genai) | Studied whether generative AI habits and study conditions help estimate current burnout symptoms in a survey of 97 university students. Compared an eight-input random forest with a workload-only logistic regression baseline. |
| [DBLP research platform](https://github.com/aliomar139/DBLP_Project) | Built a search and analytics platform for more than 8.7 million computer science publications. It combines keyword and semantic search, uses read-only DuckDB queries to answer questions in plain language, and has a React dashboard for exploring authors, venues, and publication trends. |
| [KDownloader](https://github.com/aliomar139/KDownloader) | Built an Android app that uses yt-dlp and FFmpeg to save media from shared links as MP4 video or MP3 audio. A foreground service keeps downloads running when the app is in the background, and Room stores a searchable download history on the device. |

[Email me](mailto:aliyomar630@gmail.com) about data science, machine learning, or software projects.
