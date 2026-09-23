# Java_DataType_Range
Java has eight primitive data types, each with a fixed size and pre-defined range. The following table provides a complete breakdown of their sizes, default values, and exact ranges
Java Data Type Range Formula: **2ⁿ − 1**. Learn how the number of bits (n) determines the maximum value a Java data type can store. For signed types, the range is **−2ⁿ⁻¹ to 2ⁿ⁻¹ − 1**. A simple formula to understand Java primitive data type ranges.
# Java Data Type Range


This repository explains the range of Java data types using simple formulas.

### Formula

For an **n-bit unsigned value**:
**Range = 0 to 2ⁿ − 1**

For an **n-bit signed value**:
**Range = −2ⁿ⁻¹ to 2ⁿ⁻¹ − 1**

It includes examples and explanations to help beginners understand how Java data type ranges are calculated.

Java Primitive Data Types and RangesData TypeSizeDefault ValueRange (Inclusive)Description / Formulabyte8 bits (1 byte)0-128 to 127Signed integer (-2⁷ to 2⁷-1)short16 bits (2 bytes)0-32,768 to 32,767Signed integer (-2¹⁵ to 2¹⁵-1)int32 bits (4 bytes)0-2,147,483,648 to 2,147,483,647Signed integer (-2³¹ to 2³¹-1)long64 bits (8 bytes)0L-9,223,372,036,854,775,808 to 9,223,372,036,854,775,807Signed integer (-2⁶³ to 2⁶³-1)float32 bits (4 bytes)0.0f± 1.40239846 × 10⁻⁴⁵ to ± 3.40282347 × 10³⁸Single-precision IEEE 754 floating-pointdouble64 bits (8 bytes)0.0d± 4.9406564584124654 × 10⁻³²⁴ to ± 1.7976931348623157 × 10³⁸⁸Double-precision IEEE 754 floating-pointchar16 bits (2 bytes)'\u0000''\u0000' to '\uffff' (0 to 65,535)Unsigned Unicode characterbooleanJVM dependentfalsetrue or falseRepresents a single logical bit of information
