from youtube_transcript_api import YouTubeTranscriptApi

def retrieve_sub(url):
  '''
  extract the video url id, then using YouTubeTranscriptApi.get_transcript to get
  the subtitles during the video

  parameter: youtube url
  return: dict {text:'', start:'', duration:''}

  '''
  video_id = url.replace('https://www.youtube.com/watch?v=','')
  transcript = YouTubeTranscriptApi.get_transcript(video_id)
  return transcript
