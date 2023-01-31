from pytube import YouTube

link = input("Введите ссылку на видео")
video = YouTube(link)
quality = input("Выберите качество видео (High/Low) " )

if quality == "High":
    output = video.streams.get_highest_resolution()
if quality == "Low":
    output == video.streams.get_lowest_resolution()

output.download()
