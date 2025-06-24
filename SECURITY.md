# Security Policy

## 🔒 Supported Versions

We actively maintain security for the following versions of Xonotic:

| Version | Supported          |
| ------- | ------------------ |
| 0.8.6   | ✅ Full support    |
| 0.8.5   | ✅ Security fixes  |
| 0.8.2   | ❌ No longer supported |
| < 0.8.2 | ❌ No longer supported |

## 🚨 Reporting Security Vulnerabilities

### Quick Response Commitment
- **Initial response**: Within 48 hours
- **Status updates**: Weekly until resolved
- **Fix timeline**: 30 days for critical issues

### How to Report
**Do NOT create public GitHub issues for security vulnerabilities.**

Instead, please report security issues via:

#### Email (Preferred)
- **Email**: security@xonotic.org
- **Subject**: [SECURITY] Brief description
- **Encryption**: Use GPG key if possible

#### Private Disclosure
1. Email us at security@xonotic.org
2. Include detailed reproduction steps
3. Provide affected versions
4. Suggest potential impact assessment

### What to Include
```
- Vulnerability type
- Affected component(s)
- Affected versions
- Step-by-step reproduction
- Potential impact
- Any proof-of-concept code
- Suggested mitigation (optional)
```

## 🛡️ Security Scope

### In Scope
- **Game client vulnerabilities**
- **Server-side security issues**
- **Network protocol weaknesses**
- **File format vulnerabilities**
- **Authentication bypasses**
- **Privilege escalation**
- **Remote code execution**
- **Denial of service attacks**

### Out of Scope
- **Social engineering**
- **Physical access attacks**
- **Issues in third-party dependencies** (report to upstream)
- **Theoretical attacks without practical impact**
- **Issues requiring physical access to victim's machine**

## 🔍 Common Vulnerability Categories

### Client-Side
- **Map/content loading exploits**
- **Demo file parsing vulnerabilities**
- **Buffer overflows in rendering**
- **Input validation issues**

### Server-Side
- **Remote command execution**
- **SQL injection** (if applicable)
- **Authentication bypass**
- **Privilege escalation**

### Network
- **Protocol vulnerabilities**
- **Packet flooding attacks**
- **Man-in-the-middle weaknesses**
- **Amplification attacks**

## 🏆 Responsible Disclosure

### Our Commitment
1. **Acknowledge** receipt within 48 hours
2. **Investigate** and validate the issue
3. **Develop** a fix with appropriate timeline
4. **Test** the fix thoroughly
5. **Release** patched version
6. **Credit** the reporter (if desired)

### Reporter Recognition
- **Hall of Fame**: Security researchers page
- **Credits**: In release notes and game credits
- **Swag**: Xonotic merchandise (for significant findings)
- **Early Access**: Beta versions of fixes

### Disclosure Timeline
```
Day 0:     Issue reported
Day 1-2:   Initial response and triage
Day 3-7:   Investigation and validation
Day 8-30:  Fix development and testing
Day 31:    Public disclosure and patch release
```

## 🛠️ Security Measures

### Current Protections
- **Input validation** on all user data
- **Sandboxed** map/content loading
- **Network protocol** integrity checks
- **Server admin** authentication systems
- **Rate limiting** on network operations

### Continuous Improvement
- **Regular security audits**
- **Dependency vulnerability scanning**
- **Static code analysis**
- **Penetration testing**
- **Community security reviews**

## 🚀 Security Best Practices

### For Players
- **Download** only from official sources
- **Keep** game updated to latest version
- **Avoid** suspicious custom content
- **Report** unusual behavior immediately

### For Server Administrators
- **Regular updates** to latest version
- **Secure server** configuration
- **Monitor** server logs for anomalies
- **Limit** admin privileges appropriately
- **Backup** server data regularly

### For Developers
- **Input validation** on all user data
- **Secure coding** practices
- **Regular testing** of security features
- **Code review** focus on security
- **Stay informed** about security trends

## 📋 Security Checklist

### Before Reporting
- [ ] Confirmed issue exists in latest version
- [ ] Checked if already reported
- [ ] Gathered complete reproduction steps
- [ ] Assessed potential impact
- [ ] Prepared clear description

### After Reporting
- [ ] Received acknowledgment from team
- [ ] Provided additional info if requested
- [ ] Avoided public disclosure until fixed
- [ ] Tested proposed fix if provided

## 🔗 Additional Resources

### Security Tools
- **Static Analysis**: Integrated in CI/CD
- **Dynamic Testing**: Regular penetration tests
- **Dependency Scanning**: Automated vulnerability checks

### External Security
- **CVE Database**: Check for known vulnerabilities
- **Security Forums**: General security community
- **Game Security**: Specialized gaming security resources

### Contact Information
- **General Security**: security@xonotic.org
- **Critical Issues**: security-urgent@xonotic.org
- **GPG Key**: Available on keyservers
- **Response Time**: 48 hours maximum

## 🙏 Thanks

We appreciate the security research community's efforts to keep Xonotic safe and secure for all players. Your responsible disclosure helps protect our entire community.

**Special thanks to all security researchers who have helped improve Xonotic!**

---

*This security policy is reviewed and updated regularly to ensure it meets current best practices.* 