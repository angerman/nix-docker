FROM lnl7/nix:2017-10-07

RUN nix-env -f '<nixpkgs>' -iA \
    curl \
    findutils \
    git \
    glibc \
    gnugrep \
    gnused \
    gnutar \
    jq \
    nix \
    nix-repl \
    procps \
    silver-searcher \
    vim \
    which \
 && nix-store --gc
