# Ansible Pushover
Send notifications via Pushover (https://pushover.net)

```
> PUSHOVER

  Send notifications via Pushover (https://pushover.net)

Options (= is mandatory):

= message
        Message to send in the notification

- timeout
        Timeout for URL request [Default: 10]

= token
        Your Pushover application token

- url
        The URL for the Pushover API [Default:
        https://api.pushover.net/1/messages.json]

- url_password
        The password for use in HTTP basic authentication. If the
        `url_username' parameter is not specified, the `url_password'
        parameter will not be used.

- url_username
        The username for use in HTTP basic authentication. This
        parameter can be used without `url_password' for sites that
        allow empty passwords.

- use_proxy
        if `no', it will not use a proxy, even if one is defined in an
        environment variable on the target hosts. (Choices: yes, no)
        [Default: yes]

= user
        The key of the user to send the notification to

- validate_certs
        If `no', SSL certificates will not be validated. This should
        only be used on personally controlled sites using self-signed
        certificates. (Choices: yes, no) [Default: yes]

Requirements:  pushover appliction token, and user key
```

