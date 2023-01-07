
![image](https://user-images.githubusercontent.com/36617233/211151749-586c919e-b5d6-4ad0-bfac-f0962987aba1.png)

# :punch: Task
---
The goal of the challenge is to develop a system for the task of automatic playlist continuation. Given a set of playlist features, participants' systems shall generate a list of recommended tracks that can be added to that playlist, thereby "continuing" the playlist. We define the task formally as follows:

# :punch: Input
---
A user-created playlist, represented by:
Playlist metadata (see the dataset README)
K seed tracks: a list of K tracks in the playlist, where K can equal 0, 1, 5, 10, 25, or 100.
Output

A list of 500 recommended candidate tracks, ordered by relevance in decreasing order.
Note that the system should also be able to cope with playlists for which no initial seed tracks are given! To assess the performance of a submission, the output track predictions are compared to the ground truth tracks ("reference set") from the original playlist.


# :paperclip: Dataset
---
https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge/dataset_files

# :page_facing_up: Challenge Specifications & Publications
---
https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge

https://www.recsyschallenge.com/2018/

# :mag: Citation
---
C.W. Chen, P. Lamere, M. Schedl, and H. Zamani. Recsys Challenge 2018: Automatic Music Playlist Continuation. In Proceedings of the 12th ACM Conference on Recommender Systems (RecSys ’18), 2018.
