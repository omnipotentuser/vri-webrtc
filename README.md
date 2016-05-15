#
# vri-webrtc

Engine that powers the OpenVRI which exploits RTCPeerConnection and wraps it into a module for general purpose.

vri_server/* pertains to the server side using Socket.io as the pub/sub to act as the signaler for WebRTC.
vri_client/* pertains to the client side using WebRTC PeerConnection library and socket.io client for signaling SDP and ICE candidates.

vri_server/config.js needs a token from Xirsys.com in order to utilize STUN/TURN for p2p to be functional in enterprise environments.

*API coming soon.*

# Published by: Nicholas Buchanan
# Date of Origin: May 15, 2016
