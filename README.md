# go-install

go-install - download and extract a [golang official binary](https://golang.org/dl/) to /usr/local/go


## Installation

    $ gem install go-install

## Usage

```
go-install version

Examples
$ sudo go-install latest
$ sudo go-install 1.11.1
$ sudo go-install 1.10.4

PATH setting
export PATH=$PATH:/usr/local/go/bin
export PATH=$PATH:$HOME/go/bin
```

## Examples

[centos7_golang.sh](https://gist.github.com/s3fxn/e1f3026722b0d074c34223a2cf60cece)

[ubuntu18.04_golang.sh](https://gist.github.com/s3fxn/554de2d09a948d4a563a15ad1fe4db01)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/s3fxn/go-install.

## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
