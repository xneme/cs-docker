FROM ruby:2.6.0

RUN apt-get update -yqq && apt-get install -yqq --no-install-recommends nodejs

WORKDIR /
COPY . .

RUN bundle install
RUN rails db:migrate
EXPOSE 3000
CMD ["rails", "s"]
