package(default_visibility = ['PUBLIC'])

go_get(
    name = 'logging',
    get = 'github.com/op/go-logging',
    revision = '0882c9abce533ab4afbab5677fcef7434dd36d5a',
)

go_get(
    name = 'terminal',
    get = 'golang.org/x/crypto/ssh/terminal',
    revision = '7b85b097bf7527677d54d3220065e966a0e3b613',
)

go_get(
    name = 'cover',
    get = 'golang.org/x/tools/cover',
    revision = 'c0008c5889c0d5091cdfefd2bfb08bff96527879',
)

go_get(
    name = 'gcfg',
    get = 'gopkg.in/gcfg.v1',
    revision = 'a3bc0742e3bbfd16123e6cee742cadec9a3301d2',
    patch = 'gcfg_dynamic_fields.patch',
)

go_get(
    name = 'go-bindata',
    get = 'github.com/jteeuwen/go-bindata/...',
    revision = 'a0ff2567cfb70903282db057e799fd826784d41d',
    binary = True,
)

go_get(
    name = 'go-flags',
    get = 'github.com/jessevdk/go-flags',
    revision = '0a28dbe50f23d8fce6b016975b964cfe7b97a20a',
)

go_get(
    name = 'humanize',
    get = 'github.com/dustin/go-humanize',
    revision = '8929fe90cee4b2cb9deb468b51fb34eba64d1bf0',
)

go_get(
    name = 'mux',
    get = 'github.com/gorilla/mux',
    revision = '9c068cf16d982f8bd444b8c352acbeec34c4fe5b',
    deps = [
        ':gorilla_context',
    ],
)

go_get(
    name = 'gorilla_context',
    get = 'github.com/gorilla/context',
    revision = '1c83b3eabd45b6d76072b66b746c20815fb2872d',
)

go_get(
    name = 'grpc',
    get = 'google.golang.org/grpc',
    revision = 'ecd68681d46b97d7c84e7c7d12ee7a04c138a9fa',
    deps = [
        ':protobuf',
    ],
)

go_get(
    name = 'protoc-gen-go',
    get = 'github.com/golang/protobuf/protoc-gen-go',
    revision = '087949061006daa57b3a3be58d77092cf65f6cf7',
    binary = True,
)

go_get(
    name = 'protobuf',
    get = 'github.com/golang/protobuf/proto',
    revision = '2402d76f3d41f928c7902a765dfc872356dd3aad',
)

go_get(
    name = 'testify',
    get = 'github.com/stretchr/testify',
    revision = 'f390dcf405f7b83c997eac1b06768bb9f44dec18',
)

go_get(
    name = 'osext',
    get = 'github.com/kardianos/osext',
    revision = '29ae4ffbc9a6fe9fb2bc5029050ce6996ea1d3bc',
)

go_get(
    name = 'prompter',
    get = 'github.com/Songmu/prompter',
    revision = 'f49666b0047d12850875d771340e1d862d9e7a0c',
    deps = [
        ':terminal',
    ],
)