audio-reactive glsl sandbox forked from doob's glsl-sandbox

for rapid prototyping of concert visuals

### setup

1. `bundle install`
2. `export MONGOHQ_URL="mongodb://[user]:[password]@127.0.0.1:27017/[database]"`

### run it

1. start mongo (`mongod`)
2. `bundle exec rackup config.ru`
3. hit `http://localhost:9292`

### shader uniforms

declare `uniform audio[N]` where N = your audio buffer size

### todo

1. https so chrome doesn't ask for microphone access every time
2. controls for fading/transitioning
