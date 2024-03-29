UTF-8 is a variable-length character encoding standard used for electronic communication. Defined by the Unicode Standard, the name is derived from Unicode (or Universal Coded Character Set) Transformation Format – 8-bit.[1]

UTF-8 is capable of encoding all 1,112,064[a] valid character code points in Unicode using one to four one-byte (8-bit) code units. Code points with lower numerical values, which tend to occur more frequently, are encoded using fewer bytes. It was designed for backward compatibility with ASCII: the first 128 characters of Unicode, which correspond one-to-one with ASCII, are encoded using a single byte with the same binary value as ASCII, so that valid ASCII text is valid UTF-8-encoded Unicode as well.

UTF-8 was designed as a superior alternative to UTF-1, a proposed variable-length encoding with partial ASCII compatibility which lacked some features including self-synchronization and fully ASCII-compatible handling of characters such as slashes. Ken Thompson and Rob Pike produced the first implementation for the Plan 9 operating system in September 1992.[2][3] This led to its adoption by X/Open as its specification for FSS-UTF,[4] which would first be officially presented at USENIX in January 1993[5] and subsequently adopted by the Internet Engineering Task Force (IETF) in RFC 2277 (BCP 18)[6] for future internet standards work, replacing Single Byte Character Sets such as Latin-1 in older RFCs.

UTF-8 results in fewer internationalization issues[7][8] than any alternative text encoding, and it has been implemented in all modern operating systems, including Microsoft Windows, and standards such as JSON, where, as is increasingly the case, it is the only allowed form of Unicode.

UTF-8 is the dominant encoding for the World Wide Web (and internet technologies), accounting for 98.0% of all web pages, 99.0% of the top 10,000 pages, and up to 100% for many languages, as of 2023.[9] Virtually all countries and languages have 95% or more use of UTF-8 encodings on the web.

Naming
The official name for the encoding is UTF-8, the spelling used in all Unicode Consortium documents. Most standards officially list it in upper case as well, but all that do are also case-insensitive and utf-8 is often used in code.[citation needed]

Some other spellings may also be accepted by standards, e.g. web standards (which include CSS, HTML, XML, and HTTP headers) explicitly allow utf8 (and disallow "unicode") and many aliases for encodings.[10] Spellings with a space e.g. "UTF 8" should not be used. The official Internet Assigned Numbers Authority also lists csUTF8 as the only alias,[11] which is rarely used.

In Windows, UTF-8 is codepage 65001[12] (i.e. CP_UTF8 in source code).

In MySQL, UTF-8 is called utf8mb4[13] (with utf8mb3, and its alias utf8, being a subset encoding for characters in the Basic Multilingual Plane[14]). In HP PCL, the Symbol-ID for UTF-8 is 18N.[15]

In Oracle Database (since version 9.0), AL32UTF8[16] means UTF-8. See also CESU-8 for an almost synonym with UTF-8 that rarely should be used.

UTF-8-BOM and UTF-8-NOBOM are sometimes used for text files which contain or do not contain a byte order mark (BOM), respectively.[citation needed] In Japan especially, UTF-8 encoding without a BOM is sometimes called UTF-8N.[17][18]
