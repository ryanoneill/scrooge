java_thrift_library(name='thrift',
  sources=['user.thrift'],
  compiler='scrooge',
  language='scala',
  rpc_style='finagle',
  namespace_map={
    'com.twitter.demo.thriftscala': 'com.twitter.mydemo.renamed',
  },
)
