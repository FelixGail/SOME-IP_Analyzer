.. java:import:: org.jnetpcap Pcap

.. java:import:: org.jnetpcap PcapIf

.. java:import:: org.jnetpcap.nio JMemory

.. java:import:: org.jnetpcap.packet PcapPacket

.. java:import:: org.jnetpcap.protocol.lan Ethernet

.. java:import:: org.jnetpcap.protocol.network Ip4

.. java:import:: org.jnetpcap.protocol.tcpip Udp

.. java:import:: com.espertech.esper.client EPRuntime

.. java:import:: java.util.concurrent Executors

.. java:import:: java.util.concurrent ExecutorService

.. java:import:: java.io File

.. java:import:: java.net UnknownHostException

.. java:import:: java.util ArrayList

SomeIPParser
============

.. java:package:: surf.SomeIPAnalyzer
   :noindex:

.. java:type:: public class SomeIPParser

   SomeIP Parser Class.

Methods
-------
inputFromFile
^^^^^^^^^^^^^

.. java:method:: public static void inputFromFile(String filename, EPRuntime cepRT)
   :outertype: SomeIPParser

   Read a single File and send every Paket to the Esper Engine.

   :param filename: .pcap file to read
   :param cepRT: Esper Engine the parsed paket is sent to

inputFromInterface
^^^^^^^^^^^^^^^^^^

.. java:method:: public static void inputFromInterface(String interfaceI, EPRuntime cepRT)
   :outertype: SomeIPParser

   Cpature from interface and send every Paket to the Esper Engine.

   :param interfaceI: interface to capture from
   :param cepRT: Esper Engine the parsed paket is sent to

