Name: Vimeo PCAP
Description: Users will be given a PCAP file containing a capture done on a video on vimeo. They will have to extract the video from the file and then either type the text in the video into a binary to text converter or simply use OCR to extract it. Extraction simply consists of first opening the file in wireshark and saving it as a Wireshark/tcpdump pcap and then running the included videosucker.py file as follows:

./videosucker.py -p capture.pcap -o output

And then taking the output and OCR'ing it or manually typing it and using that to convert from binary to text and extract the key.

Files to distribute: capture.pcap

Flag: MCA-58BE147A