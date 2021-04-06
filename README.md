GraphRequest request = GraphRequest.newPostRequest(
  accessToken,
  "/EAACiurEB6xYBAEzLpfIWhiNGM7Nr5lAq7JjwyqtDWZBsillgk1CdHNG9Y9MZCZBVFvVdvgzc28ZAlssMdc0y1tthZCURkpeR5fOxTZApRJB8LrOcCwZCsoZACEZCpTg87mDlQ3yjDdbRj5sISz0sDeFBZB4Nv5CRZB4H1DB9qxIZBd7MGE2mFNWukuZC4cHSGZCeD5IucYU06e3sZBPG0U8HNSSl3KZCdsxJ21LX7h4ZD",
  new JSONObject("{\"RightHands BJ Shop\":\"www.righthandsbj.company.site\",\"Youtube\":\"www.youtube.com/c/RightHandsBJOfficial\",\"Facebook Fanspage Official\":\"www.facebook.com/righthandsbj\"}"),
  new GraphRequest.Callback() {
    @Override
    public void onCompleted(GraphResponse response) {
      // Insert your code here
    }
});
request.executeAsync();
