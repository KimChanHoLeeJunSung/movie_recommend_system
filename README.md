# movie_recommend_system

data는 kaggle에 있는 movie.csv, rating.csv를 이용하였다.
https://www.kaggle.com/grouplens/movielens-20m-dataset

아직 엔진만 기초적으로 만든 상황이며 추후 프론트,백엔드를 만들 예정이다.

엔진 기초적 원리 ( collaborative filtering )
  1. 사용자의 id 를 입력한다.
  2. 다른 사용자들중 사용자가 평점을 매긴 영화들과 비슷한 사람들을 뽑는다.
  3. 그 사람들이 본 영화들중 사용자가 안 본 영화들을 모은다.
  4. 그 중에서 평점이 높은 순으로 사용자에게 추천을 해준다.

추후 엔진에 추가할 내용
  1. NLP를 이용하여 리뷰에 대한 점수를 매겨 평점과 합쳐 계산할 예정
