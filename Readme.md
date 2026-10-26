A lightweight Alpine‑based container image that bundles pypandoc with uv and Python for fast, dependency‑free document conversions

#1 [internal] load local bake definitions
#1 reading from stdin 439B done
#1 DONE 0.0s

#2 [internal] load build definition from Containerfile
#2 transferring dockerfile: 241B 0.0s done
#2 DONE 0.0s

#3 [auth] pandoc/core:pull token for registry-1.docker.io
#3 DONE 0.0s

#4 [internal] load metadata for docker.io/pandoc/core:latest
#4 DONE 0.7s

#5 [internal] load .dockerignore
#5 transferring context: 2B done
#5 DONE 0.0s

#6 [1/3] FROM docker.io/pandoc/core:latest@sha256:62518bfb6833705dc90a1634d8d879299bd820b3f74ad3b32fba8b618452553a
#6 resolve docker.io/pandoc/core:latest@sha256:62518bfb6833705dc90a1634d8d879299bd820b3f74ad3b32fba8b618452553a done
#6 extracting sha256:75262caa75d83094c6c4bf507ac694bca9040c63603f70bc0dc1cb10e5375234 done
#6 sha256:faa1fa6e301541618abb750af461982d8fcd716278765723d119317ec1c024ff 4.68kB / 4.68kB done
#6 sha256:5f85d2bf0547f1455d5658e8be674d44a2957a2434f088daeda3058dbbd2a784 0B / 755.87kB 0.1s
#6 sha256:f73cf88ddaaef56fb07fd6646b2939f812fff99085f451ec3c3a17f338f8b34b 1.44kB / 1.44kB done
#6 sha256:75262caa75d83094c6c4bf507ac694bca9040c63603f70bc0dc1cb10e5375234 94B / 94B 0.1s done
#6 sha256:b2041f4799b311c7f22ab25628b96f63ad9b98224b781c9c31779efc65b16d4d 0B / 30.67MB 0.1s
#6 sha256:eb916303d19d9dc10394629d7a5f7e99efcf5868329de22de36b35911d0f8c92 0B / 10.51MB 0.1s
#6 sha256:62518bfb6833705dc90a1634d8d879299bd820b3f74ad3b32fba8b618452553a 1.61kB / 1.61kB done
#6 sha256:b2041f4799b311c7f22ab25628b96f63ad9b98224b781c9c31779efc65b16d4d 4.19MB / 30.67MB 0.2s
#6 sha256:5f85d2bf0547f1455d5658e8be674d44a2957a2434f088daeda3058dbbd2a784 755.87kB / 755.87kB 0.3s
#6 sha256:b2041f4799b311c7f22ab25628b96f63ad9b98224b781c9c31779efc65b16d4d 22.02MB / 30.67MB 0.4s
#6 sha256:eb916303d19d9dc10394629d7a5f7e99efcf5868329de22de36b35911d0f8c92 1.05MB / 10.51MB 0.4s
#6 sha256:b2041f4799b311c7f22ab25628b96f63ad9b98224b781c9c31779efc65b16d4d 30.67MB / 30.67MB 0.5s
#6 sha256:eb916303d19d9dc10394629d7a5f7e99efcf5868329de22de36b35911d0f8c92 4.19MB / 10.51MB 0.5s
#6 sha256:5f85d2bf0547f1455d5658e8be674d44a2957a2434f088daeda3058dbbd2a784 755.87kB / 755.87kB 0.4s done
#6 sha256:eb916303d19d9dc10394629d7a5f7e99efcf5868329de22de36b35911d0f8c92 10.51MB / 10.51MB 0.6s
#6 sha256:b2041f4799b311c7f22ab25628b96f63ad9b98224b781c9c31779efc65b16d4d 30.67MB / 30.67MB 0.8s done
#6 sha256:bfad002045509d17a67c47e2b03a7d638d9303bafe6ec2f2f9a76cc6a23d6e02 9.44MB / 12.17MB 0.9s
#6 sha256:eb916303d19d9dc10394629d7a5f7e99efcf5868329de22de36b35911d0f8c92 10.51MB / 10.51MB 0.9s done
#6 sha256:bfad002045509d17a67c47e2b03a7d638d9303bafe6ec2f2f9a76cc6a23d6e02 12.17MB / 12.17MB 1.1s done
#6 extracting sha256:b2041f4799b311c7f22ab25628b96f63ad9b98224b781c9c31779efc65b16d4d
#6 extracting sha256:b2041f4799b311c7f22ab25628b96f63ad9b98224b781c9c31779efc65b16d4d 0.3s done
#6 extracting sha256:5f85d2bf0547f1455d5658e8be674d44a2957a2434f088daeda3058dbbd2a784
#6 extracting sha256:5f85d2bf0547f1455d5658e8be674d44a2957a2434f088daeda3058dbbd2a784 0.0s done
#6 extracting sha256:eb916303d19d9dc10394629d7a5f7e99efcf5868329de22de36b35911d0f8c92 0.1s
#6 extracting sha256:eb916303d19d9dc10394629d7a5f7e99efcf5868329de22de36b35911d0f8c92 0.1s done
#6 extracting sha256:bfad002045509d17a67c47e2b03a7d638d9303bafe6ec2f2f9a76cc6a23d6e02
#6 extracting sha256:bfad002045509d17a67c47e2b03a7d638d9303bafe6ec2f2f9a76cc6a23d6e02 0.1s done
#6 DONE 7.0s

#7 [2/3] RUN apk add --no-cache uv python3
#7 1.193 ( 1/10) Installing gdbm (1.26-r0)
#7 1.207 ( 2/10) Installing libstdc++ (15.2.0-r5)
#7 1.261 ( 3/10) Installing mpdecimal (4.0.1-r0)
#7 1.275 ( 4/10) Installing libpanelw (6.6_p20260516-r0)
#7 1.286 ( 5/10) Installing sqlite-libs (3.53.4-r0)
#7 1.332 ( 6/10) Installing python3 (3.14.8-r0)
#7 1.564 ( 7/10) Installing python3-pycache-pyc0 (3.14.8-r0)
#7 1.664 ( 8/10) Installing pyc (3.14.8-r0)
#7 1.664 ( 9/10) Installing python3-pyc (3.14.8-r0)
#7 1.664 (10/10) Installing uv (0.11.19-r1)
#7 1.810 Executing busybox-1.37.0-r31.trigger
#7 1.827 OK: 98.5 MiB in 65 packages
#7 DONE 2.3s

#8 [3/3] WORKDIR /work
#8 DONE 0.0s

#9 exporting to image
#9 exporting layers
#9 exporting layers 0.3s done
#9 writing image sha256:133919677ccb87402f4dfc2b84df773f6b3ebd21da6e6fa56a8515bdbfa8a6d1 done
#9 naming to docker.io/library/pypandoc-alpine-uv-test done
#9 DONE 0.3s

#10 resolving provenance for metadata file
#10 DONE 0.0s
