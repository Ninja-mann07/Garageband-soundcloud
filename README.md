# Garageband-soundcloud
 Song uploads
curl -X 'POST' \
  'https://api.soundcloud.com/tracks' \
  -H 'accept: application/json; charset=utf-8' \
  -H 'Content-Type: multipart/form-data' \
  -F 'track[permalink]=https://api.soundcloud.com/tracks/308946187' \
  -F 'track[release]=' \
  -F 'track[release_date]=' \
  -F 'track[tag_list]=' \
  -F 'track[genre]=' \
  -F 'track[downloadable]=true' \
  -F 'track[license]=' \
  -F 'track[description]=' \
  -F 'track[sharing]=public' \
  -F 'track[isrc]=' \
  -F 'track[streamable]=true' \
  -F 'track[asset_data]=@Badass.band.zip;type=application/zip' \
  -F 'track[commentable]=true' \
  -F 'track[title]=badass' \
  -F 'track[label_name]=' \
  -F 'track[artwork_data]=@CullenJarvis_GettingConnected.pptx;type=application/vnd.openxmlformats-officedocument.presentationml.presentation' \
  -F 'track[embeddable_by]=' \
  -F 'track[purchase_url]='
