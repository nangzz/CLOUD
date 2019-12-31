## 1. 네트워크 주소체계(IP4)
1. A 클래스
|0|
1~126
사설 ip:10번으로 시작
2. B 클래스
|10|
128~191
사설 ip: 172.16~172.31
3. C 클래스
|110|. 0000
192~223
사설IP: 192.168.0~192.168.255

- 네트워크(서브넷)  주소: 192.168.0
- broadcast주소 : 192.168.255
- DNS: 10.0.0.2
- DHCP: 

## 2. 네트워크 정책
- 화이트리스트 정책 :
기본적으로 방화벽으로 다 막아놓고 특정 포트만 허용하는 정책
- 블랙리스트 정책:
기본적으로 다 허용이지만 특정 포트나 iP만 막는정책


ip netns
ip netns exec qrouter-bb2cfe20-fa71-4e31-ae6d-cdf5b1eb0a87 ssh -i key/openstack.pem cirros@10.0.0.211