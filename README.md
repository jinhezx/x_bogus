def gen_x_bogus(url, ua=''):
    xbogus = ""
    try:
        xbogus = os_x.call('sign', url, ua)
    except Exception as e:
        op_error(e)
    return xbogus

Q:120525183
