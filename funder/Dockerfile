FROM ghcr.io/foundry-rs/foundry:nightly-ac802618e15039b31e464ae6d1fe3ee39f87cefd

RUN apk add jq
ADD funder.sh /
#RUN chmod a+rx /funder.sh
ENTRYPOINT  /funder.sh 
