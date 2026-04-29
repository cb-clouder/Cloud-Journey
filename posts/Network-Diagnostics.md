In this lesson, I learned about ICMP and Traceroute which are both helpful tools in diognosing network issues. I reviewed exampled of ICMP and Traceroute readings to help diagnose network problems and failures. 

## ICMP
- Internet Control Message Protocol (ICMP): A network layer protocol used for sending error messages and diagnostic information, such as “destination unreachable” or “time exceeded.” It supports tools like ping and traceroute to help identify and fix network problems.
- Companion of Internet Protocol (IP) working alongside it in the network layer.
- Utilizes Echo messages
      - Echo Request: A device sends this message to ask another device if it is reachable.
      - Echo Reply: If the other device is available, it responds to confirm that it received the request.
- Uses Ping: A diagnostic tool that uses ICMP Echo Requests and Echo Replies to test whether another device is reachable and to measure how long it takes for a message to travel to that device and back.

## Traceroute
- A network diagnostic tool that maps the path packets take to a destination by sending packets with increasing TTL values and receiving ICMP “time exceeded” messages from each router along the way.
- Hop; A single step that a packet takes as it moves from one device (usually a router) to the next across a network. Traceroute measures each hop along the path to the destination.
- ICMP Time Exceeded: A message sent by a router when a packet’s TTL reaches zero, used by traceroute to reveal the router’s presence along the path.
